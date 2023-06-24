1. Chạy với MacOS
    Cách 1: 
        - Dùng lệnh open -a'Visual Studio Code'/đường dẫn thư mục
    Cách 2: Config để dùng lệnh ngắn hơn
        - Mở ~/.bash_profile hoặc ~/.zshrc bằng : nano ~/.bash_profile (nano ~/.zshrc).
        - Tạo một alisa: alias code='open -a"Visual Studio Code"'
        - ctrl X để lưu, nhấn y và enter để hoàn thành và thoát ra
        - source ~/.bash_profile (source ~/.zshrc) để tải lại file cấu hình
        - sau đó mở file bằng: code + path_của_folder