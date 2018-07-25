FROM microsoft/dotnet:2.1-aspnetcore-runtime

COPY certificateAuthorityCertificate.pem /usr/local/share/ca-certificates/

RUN update-ca-certificates