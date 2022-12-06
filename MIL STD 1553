Python 3.10.2 (v3.10.2:a58ebcc701, Jan 13 2022, 14:50:16) [Clang 13.0.0 (clang-1300.0.29.30)] on darwin
Type "help", "copyright", "credits" or "license()" for more information.
from hashlib import pbkdf2_hmac
our_app_iters = 500_000
dk = pbkdf2_hmac('sha256', b'password', b'bad salt'*2, our_app_iters)
dk.hex()
'15530bba69924174860db778f2c6f8104d3aaf9d26241840c8c4a641c8d000a9'
