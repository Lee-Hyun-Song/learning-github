# Lecture Note on Shell Commands

### 202135569 이현송

## 1. pwd (Print Working Directory)
- **명령어**: `pwd`
- **설명**: 현재 작업 디렉터리의 경로를 출력합니다.
- **사용 예시**:
    ```bash
    $ pwd
    /home/user
    ```

## 2. cd (Change Directory)
- **명령어**: `cd [directory]`
- **설명**: 다른 디렉터리로 이동할 때 사용합니다.
- **주요 옵션**:
    - `/`: 루트 디렉터리로 이동
    - `..`: 상위 디렉터리로 이동
    - `~`: 사용자 홈 디렉터리로 이동
- **사용 예시**:
    ```bash
    $ cd /home/user/Documents
    ```

## 3. ls (List)
- **명령어**: `ls`
- **설명**: 현재 디렉터리의 파일 및 디렉터리 목록을 출력합니다.
- **주요 옵션**:
    - `-l`: 자세한 정보를 함께 출력 (long format)
    - `-lh`: 파일 크기를 사람이 읽을 수 있는 단위로 출력
- **사용 예시**:
    ```bash
    $ ls -lh
    total 12K
    -rw-r--r-- 1 user group 1.2K Sep 25 12:00 file.txt
    ```

## 4. cp (Copy)
- **명령어**: `cp [source] [destination]`
- **설명**: 파일이나 디렉터리를 복사합니다.
- **사용 예시**:
    ```bash
    $ cp file.txt /home/user/backup/
    ```

## 5. mv (Move or Rename)
- **명령어**: `mv [source] [destination]`
- **설명**: 파일이나 디렉터리를 이동하거나 이름을 변경할 때 사용합니다.
- **사용 예시**:
    ```bash
    $ mv oldname.txt newname.txt
    ```

## 6. rm (Remove)
- **명령어**: `rm [file]`
- **설명**: 파일을 삭제합니다. 주의: 삭제된 파일은 복구할 수 없습니다.
- **사용 예시**:
    ```bash
    $ rm file.txt
    ```

## 7. mkdir (Make Directory)
- **명령어**: `mkdir [directory name]`
- **설명**: 새 디렉터리를 생성합니다.
- **사용 예시**:
    ```bash
    $ mkdir new_folder
    ```

## 8. clear (Clear Screen)
- **명령어**: `clear`
- **설명**: 터미널 화면을 깨끗하게 지웁니다.
- **사용 예시**:
    ```bash
    $ clear
    ```

## 9. exit (Exit Terminal)
- **명령어**: `exit`
- **설명**: 터미널 세션을 종료합니다.
- **사용 예시**:
    ```bash
    $ exit
    ```

## 10. help and man
- **명령어**: `help`, `man [command]`
- **설명**: 각 명령어의 사용법에 대한 도움말을 제공합니다.
- **사용 예시**:
    ```bash
    $ help ls
    $ man ls
    ```




</footer>
