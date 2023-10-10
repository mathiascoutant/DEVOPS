FROM rust
COPY . /var/
RUN useradd -m rust
RUN chown -R rust:rust /var/
USER rust
EXPOSE 8080/tcp
WORKDIR /var/www/WIK_DPS_TP01/
CMD [ "cargo", "run" ]
