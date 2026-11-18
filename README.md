# propfirm-runner

Lịch chạy dự phòng cho web cá nhân: khi máy nhà tắt, GitHub Actions tính thay rồi đẩy dữ liệu lên Cloudflare.
Repo chỉ chứa lịch chạy; mã nằm ở kho riêng, tải bằng khoá trong Secrets.

Secrets cần có: `CLOUDFLARE_API_TOKEN`, `CF_ACCOUNT_ID`, `CF_NAMESPACE_ID`, `SITE_SECRET`.
Chạy tay: Actions → run → Run workflow (tick "force" để chạy cả khi máy nhà đang chạy).
