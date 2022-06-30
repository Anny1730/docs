{% data reusables.secret-scanning.api-beta %}

{% data variables.product.prodname_secret_scanning %} API 可让您{% ifversion fpt or ghec or ghes > 3.1 or ghae %}：

- Enable or disable {% data variables.product.prodname_secret_scanning %}{% if secret-scanning-push-protection %} and push protection{% endif %} for a repository. For more information, see "[Repositories](/rest/reference/repos#update-a-repository)" and expand the "Properties of the `security_and_analysis` object" section in the REST API documentation.
- Retrieve and update {% data variables.product.prodname_secret_scanning_GHAS %} alerts from a repository. For further details, see the sections below.
{%- else %} retrieve and update {% data variables.product.prodname_secret_scanning %} alerts from a repository.{% endif %}

有关 {% data variables.product.prodname_secret_scanning %} 的更多信息，请参阅“[关于 {% data variables.product.prodname_secret_scanning %}](/code-security/secret-security/about-secret-scanning)”。