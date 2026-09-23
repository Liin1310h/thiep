# Thiệp mời lễ tốt nghiệp

Web thiệp mời tĩnh, triển khai bằng GitHub Pages.

## Chạy local

Mở `index.html` trực tiếp trong trình duyệt. Nút dẫn đường cần chạy trên HTTPS hoặc `localhost` để trình duyệt cho phép định vị.

## Deploy

Push branch `main` lên GitHub. Workflow trong `.github/workflows/deploy.yml` sẽ tự động deploy lên GitHub Pages.

Trong repository GitHub, vào **Settings → Pages**, đặt **Source** là **GitHub Actions**. Link public sẽ có dạng `https://<username>.github.io/<repository>/`.
