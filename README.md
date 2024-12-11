# ChatGPT-3.5-Turbo

ChatGPT-3.5-Turbo là một API mạnh mẽ từ OpenAI, cho phép bạn tích hợp khả năng xử lý ngôn ngữ tự nhiên tiên tiến vào ứng dụng của mình. Với API này, bạn có thể xây dựng các ứng dụng như chatbot, phân tích ngôn ngữ, hoặc các công cụ hỗ trợ tự động hóa.

## Hướng dẫn lấy API Key từ OpenAI

Để sử dụng API ChatGPT-3.5-Turbo, bạn cần có một API Key. Thực hiện các bước sau để lấy API Key:

1. **Đăng nhập vào tài khoản OpenAI của bạn**  
   Truy cập [OpenAI API Platform](https://platform.openai.com) và đăng nhập bằng tài khoản của bạn. Nếu chưa có tài khoản, hãy đăng ký trước.

2. **Tạo API Key**  
   - Đi đến phần **API Keys** trong menu tài khoản.  
   - Nhấp vào nút **Create new secret key** để tạo một API Key mới.  
   - Sao chép key này và lưu trữ ở nơi an toàn (API Key chỉ hiển thị một lần).

3. **Lưu ý về bảo mật**  
   - Không chia sẻ API Key với bất kỳ ai.  
   - Không lưu API Key trực tiếp trong mã nguồn, đặc biệt khi mã nguồn được lưu trữ trên kho công khai.  
   - Sử dụng biến môi trường (Environment Variables) để lưu API Key. Ví dụ:  
     ```bash
     export OPENAI_API_KEY="your-api-key"
     ```
     Sau đó, bạn có thể sử dụng API Key trong Python:
     ```python
     import os
     import openai

     openai.api_key = os.getenv("OPENAI_API_KEY")
     ```

4. **Xác thực API Key**  
   Đảm bảo rằng API Key của bạn đã được kích hoạt và tài khoản của bạn có thông tin thanh toán hợp lệ để sử dụng API.

## Tài liệu liên quan
- [Hướng dẫn sử dụng OpenAI API](https://platform.openai.com/docs)
- [Best Practices for API Key Safety](https://help.openai.com/en/articles/5112595-best-practices-for-api-key-safety)

## Liên hệ
Nếu gặp vấn đề, bạn có thể tìm hỗ trợ tại [OpenAI Help Center](https://help.openai.com) hoặc [Developer Forum](https://community.openai.com).

