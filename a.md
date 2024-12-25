{
    email programmerdatch@gmail.com
}

# urholdingsgroup.rw

urholdingsgroup.rw, www.urholdingsgroup.rw {
    reverse_proxy localhost:7000
    tls {
        issuer acme
    }
}

stock.urholdingsgroup.rw {
    reverse_proxy localhost:7001
    tls {
        issuer acme
    }
}
