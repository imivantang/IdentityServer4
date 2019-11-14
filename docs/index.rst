欢迎来到 IdentityServer4 (ASP.NET Core 3.x)
=============================================

.. image:: images/logo.png
   :align: center

IdentityServer4 是一个 ASP.NET Core 下的 OpenID Connect 和 OAuth 2.0 框架。

它可以在你的应用程序中启用以下功能：

| **身份验证服务（Authentication as a Service）** 
| 适用于你所有应用程序（web, native, mobile, services）集中登录的逻辑和相关工作流程。IdentityServer4 是经 OpenID Connect `官方认证<https://openid.net/certification/>`_ 的一种实现。

| **单点登录 / 注销（Single Sign-on / Sign-out）** 
| 多种类型应用程序上的单点登录（或注销）。

| **API的访问控制（Access Control for APIs）** 
| 为各种类型的客户端发放API的访问令牌，例如：服务端到服务端、Web应用程序、单页面Web应用程序和本机（移动）端应用程序等等。

| **联合网关（Federation Gateway）**
| 支持外部身份提供商的集成（如：Azure Active Directory, Google, Facebook等等），简化你的应用程序接入流程，避免你过多的考虑这些外部身份提供商的接入细则。

| **专注于可定制（Focus on Customization）**
| 最重要的部分 - IdentityServer 可以在许多方面根据**你**的需求进行定制。因为 IdentityServer 是一个框架，而不是一个盒装产品或 SaaS 服务，所以**你**可以用编码的方式对其进行定制来适应**你**的解决方案。

| **成熟的开源（Mature Open Source）**
| IdentityServer 使用 `Apache 2 <https://www.apache.org/licenses/LICENSE-2.0>`_ 开源许可，允许在其基础之上构建商业产品。它也是 `.NET 基金会 <https://dotnetfoundation.org/>`_的一部分，基金会为其提供治理和法律支持。

| **免费或商业支持（Free and Commercial Support）**
| 如果你在构建或运行你的身份平台时需要帮助，:ref:`请告知我们 <refSupport>`。我们可以通过多种方式为你提供帮助。

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Introduction

   intro/big_picture
   intro/architecture
   intro/terminology
   intro/specs
   intro/packaging
   intro/support
   intro/test
   intro/contributing

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Quickstarts

   quickstarts/0_overview
   quickstarts/1_client_credentials
   quickstarts/2_interactive_aspnetcore
   quickstarts/3_aspnetcore_and_apis
   quickstarts/4_entityframework
   
.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Configuration

   configuration/startup
   configuration/resources
   configuration/clients
   configuration/mvc
   configuration/apis

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Topics

   topics/startup
   topics/resources
   topics/clients
   topics/signin
   topics/signin_external_providers
   topics/windows
   topics/signout
   topics/signout_external_providers
   topics/signout_federated
   topics/federation_gateway
   topics/consent
   topics/apis
   topics/deployment
   topics/logging
   topics/events
   topics/crypto
   topics/grant_types
   topics/secrets
   topics/extension_grants
   topics/resource_owner
   topics/refresh_tokens
   topics/reference_tokens
   topics/mtls
   topics/request_object
   topics/custom_token_request_validation
   topics/cors
   topics/discovery
   topics/add_apis
   topics/add_protocols
   topics/tools

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Endpoints

   endpoints/discovery
   endpoints/authorize
   endpoints/token
   endpoints/userinfo
   endpoints/device_authorization
   endpoints/introspection
   endpoints/revocation
   endpoints/endsession

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Reference

   reference/identity_resource
   reference/api_resource
   reference/client
   reference/grant_validation_result
   reference/profileservice
   reference/interactionservice
   reference/deviceflow_interactionservice
   reference/options
   reference/ef
   reference/aspnet_identity

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Misc

   misc/training
   misc/blogs
   misc/videos
