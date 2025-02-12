---
title: Habilitar la búsqueda en repositorios de GitHub.com desde tu ambiente empresarial privado
shortTitle: Buscar en GitHub.com desde una empresa
intro: 'Puedes conectar tus cuentas personales de {% data variables.product.prodname_dotcom_the_website %} y tu ambiente privado de {% data variables.product.prodname_enterprise %} para buscar contenido en repositorios específicos de {% data variables.product.prodname_dotcom_the_website %}{% ifversion fpt or ghec %} desde tu ambiente privado{% else %} desde {% data variables.product.product_name %}{% endif %}.'
redirect_from:
  - /articles/enabling-private-githubcom-repository-search-in-your-github-enterprise-account
  - /articles/enabling-private-github-com-repository-search-in-your-github-enterprise-server-account
  - /articles/enabling-private-githubcom-repository-search-in-your-github-enterprise-server-account
  - /articles/enabling-githubcom-repository-search-in-github-enterprise-server
  - /github/searching-for-information-on-github/enabling-githubcom-repository-search-in-github-enterprise-server
  - /github/searching-for-information-on-github/getting-started-with-searching-on-github/enabling-githubcom-repository-search-in-github-enterprise-server
versions:
  ghes: '*'
  ghae: '*'
topics:
  - GitHub search
---

## About search for {% data variables.product.prodname_dotcom_the_website %} repositories from {% data variables.product.product_name %}

You can search for designated private repositories on {% data variables.product.prodname_ghe_cloud %} from {% data variables.product.product_location %}{% ifversion ghae %} on {% data variables.product.prodname_ghe_managed %}{% endif %}. For more information about searching across environments, see "[About searching on GitHub](/github/searching-for-information-on-github/getting-started-with-searching-on-github/about-searching-on-github#searching-repositories-on-githubcom-from-your-private-enterprise-environment)."

## Prerrequisitos

An enterprise owner for {% data variables.product.product_name %} must enable {% data variables.product.prodname_github_connect %} and {% data variables.product.prodname_unified_search %} for private repositories. Para obtener más información, consulta la sección "[Habilitar la {% data variables.product.prodname_unified_search %} en tu empresa](/admin/configuration/configuring-github-connect/enabling-unified-search-for-your-enterprise)".

## Enabling {% data variables.product.prodname_dotcom_the_website %} repository search from {% data variables.product.product_name %}

1. Inicia sesión en {% data variables.product.product_name %} y en {% data variables.product.prodname_dotcom_the_website %}.
1. En {% data variables.product.product_name %}, en la esquina superior derecha de cualquier página, haz clic en tu foto de perfil y luego haz clic en **Ajustes**. ![Icono Settings (Parámetros) en la barra de usuario](/assets/images/help/settings/userbar-account-settings.png)
{% data reusables.github-connect.github-connect-tab-user-settings %}
{% data reusables.github-connect.connect-dotcom-and-enterprise %}
