#Learn SQL

##1. Database là gì?
    - Còn được gọi là cơ sở dữ liệu. Chịu trách nhiệm lưu giữ data cho phần mềm
    - Cơ sở dữ liệu được lưu theo dạng hàng và cột (Table)
    
##2. Component ( Có nhiều loại SQL )
    - SQL: Structure Query Language : Là ngôn ngữ truy vấn có cấu trúc (có hàng, có cột)
    - MySQL: Database Management System, NoSQL, Oracle, ..
    
##3. Thành phần của Database
    - Có 1 database (1 dự án)
    - Các table ( bảng )
    - Mỗi bảng sẽ lưu thông tin cơ bản của 1 đối tượng nào đó
    - Column ( Field ) / Row
    
##4. Các câu lệnh SQL
    1. Tạo database
    - CREATE DATABASE database_name;
    
    2. Tạo table
    - **Có 3 kiểu dữ liệu đơn giản: Số (Integer), Chữ (Varchar), Date (DATE)**

    - USE database_name; (Sử dụng database vừa tạo)

    - CREATE TABLE table_name (
        id INT,
        column VARCHAR(30),
        birth_day DATE
    )

    - CREATE TABLE table_name_1 (
        id INT,
        column_1 VARCHAR(30),
        birth_day_1 DATE
    )

    4. INSERT dữ liệu vào bảng
    INSERT INTO table_name ( id, column, birth_day )
    VALUES                 ( 1, 'BugCreator', '2023-02-01' ),
                           ( 2, 'BugCreator', '2023-02-01' );

    INSERT INTO table_name_1 ( id, column_1, birth_day_1 )
    VALUES                 ( 1, 'BugCreator', '2023-02-01' ),
                           ( 2, 'BugCreator', '2023-02-01' );
