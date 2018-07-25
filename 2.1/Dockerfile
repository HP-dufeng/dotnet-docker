FROM microsoft/dotnet:2.1-aspnetcore-runtime

COPY certificateAuthorityCertificate.pem /usr/local/share/ca-certificates/extra/certificateAuthorityCertificate.crt

RUN update-ca-certificates