- Tách các service theo các module
- Tách biệt phụ thuộc giữa các tầng thông qua interface
- Setup depencency framework, tool tại main
- Model là tầng định nghĩa data
- Business là tầng định nghĩa logic nghiệp vụ
- Transport là tầng xử lý request, response
- Storage là tầng xử lý thao tác với database.
- Tại một tầng bất kỳ: 
  - Định nghĩa struct của tầng đang xử lý
  - Định nghĩa contructor của tầng đó
  - Định nghĩa interface của tầng dưới mà sẽ inject vào struct đó. 
  - Implement interface tại tầng dưới.
  - Định nghĩa method của struct