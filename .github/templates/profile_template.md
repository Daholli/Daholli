<!-- Markdown template for metrics bot -->

<!-- template -->
I joined GitHub on `{{ f.date(REGISTRATION_DATE, {date:true}) }}`.
I contributed to `{{ REPOSITORIES_CONTRIBUTED_TO }}` repositories and made `{{ COMMITS }}` commits.


<%- await include(partials/activity.ejs) %>

<%- await embed(`example-languages-pdf`, {languages:true, languages_details:"percentage, bytes-size", config_display:"large"}) %>
