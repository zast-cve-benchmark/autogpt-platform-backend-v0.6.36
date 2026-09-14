# autogpt-platform-backend-v0.6.36 - 漏洞总览

| # | CVE | 端点 | 漏洞类型 | 状态 |
|---|---|---|---|---|
| 1 | CVE-2026-30950 | `PATCH /api/chat/sessions/{session_id}/assign-user` | IDOR/会话劫持 (CWE-639) | CODE_AUDIT |
| 2 | CVE-2026-33232 | `GET /api/store/listings/versions/{id}/graph/download` | 磁盘耗尽 DoS (CWE-400) | CODE_AUDIT |
| 3 | CVE-2026-33233 | `全局配置 (共享缓存 @cached shared_cache=True)` | 不安全反序列化 RCE (CWE-502) | CODE_AUDIT |
| 4 | CVE-2026-33234 | `SendEmailBlock config.smtp_server` | SSRF / 内网端口扫描 (CWE-918) | CODE_AUDIT |
