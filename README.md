<h1 align="center">ory-hydra-aspnetcore-consumer-app-poc</h1>

---

This is a sample consumer app for hydra built with ASP.NET core.

---
## Getting Started

1. go to https://www.ory.sh/run-oauth2-server-open-source-api-security and follow all steps until you have to create your OAuth 2.0 client. when creating you have to additional give "--token-endpoint-auth-method client_secret_post" as parameter so the token endpoint auth method is not "client_secret_basic". Now continue until you have a running login & consent provider. 
2. take client-id, client-secret and callbacks into appsettings. Authority is your callback.
3. run app 

## License

This project is licensed under the **Apache License**. This means that you can use, modify and distribute it freely. See [http://www.apache.org/licenses/LICENSE-2.0.html](http://www.apache.org/licenses/LICENSE-2.0.html) for more details.

---
<p align="center">
	<a href="https://github.com/ory/hydra">Hydra</a>
</p>
