
go get -u github.com/jackc/pgconn
go get -u github.com/jackc/pgx/v4
PostgreSQL driver and toolkit for Go.
Package pgconn is a low-level PostgreSQL database driver. 
It operates at nearly the same level as the C library libpq. It is primarily intended to serve as the foundation for higher level libraries such as https://github.com/jackc/pgx. Applications should handle normal queries with a higher level library and only use pgconn directly when required for low-level access to PostgreSQL functionality.

go get -u github.com/alexedwards/scs/v2
HTTP Session Management for Go.
Automatic loading and saving of session data via middleware.
go get -u github.com/alexedwards/scs/redisstore

github.com/go-chi/chi/v5
chi router for building Go HTTP services