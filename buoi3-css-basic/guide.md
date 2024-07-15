# CSS là gì - Cascading Style Sheets
  *  là một ngôn ngữ được sử dụng để tìm và định dạng lại các phần tử được tạo ra bởi các ngôn ngữ đánh dấu (HTML). Nói ngắn gọn hơn là ngôn ngữ tạo phong cách cho trang web.

## Tại sao cần sử dụng CSS
  - CSS cho phép bạn định nghĩa kiểu, cách hiện thị cho các phần tử HTML.
  - CSS giúp bạn kiểm soát cách hiển thị của trang web trên các thiết bị khác nhau.

### Các cách sử dụng CSS
  - Inline CSS: Viết css trực tiếp vào thẻ HTML.
    ```
    <h1 style="color:blue;">A Blue Heading</h1>
    ```
  - Internal CSS
    ```
    <head>
      <style>
        body {background-color: powderblue;}
        h1   {color: blue;}
        p    {color: red;}
      </style>
    </head>
    ```
  - External CSS: Viết css vào file riêng và gọi file đó vào file HTML.
    ```
    <head>
      <link rel="stylesheet" type="text/css" href="styles.css">
    </head>
    ```

  - Độ ưu tiên của CSS: Inline CSS > (Internal CSS  External CSS)

### ID và Class
  - ID: Được sử dụng để xác định một phần tử duy nhất.
  - Class: Được sử dụng để xác định một nhóm các phần tử.

  * Lấy ra element có id là "demo"
    - CSS cho element có id thì dùng dấu #
    ```
    #demo {
      background-color: yellow;
    }
    ```

### CSS selector
  - Selector: Là cách chúng ta chọn phần tử HTML mà chúng ta muốn áp dụng CSS.
  - Có nhiều loại selector như:
    - Element Selector
    - ID Selector
    - Class Selector
    - Descendant Selector X Y
    - Universal Selector
    - Group Selector
    - Child Selector
    - Adjacent Sibling Selector
    - Attribute Selector
    - Pseudo-class Selector
    - Pseudo-element Selector

    * Reset CSS
      ```
      * {
        margin: 0;
        padding: 0;
      }
      ```