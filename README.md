# Graphql LSP bug

Loading the `gql_lsp` workspace will have an error message.
Loading the `gql_lsp_reverse` workspace will result in it loading the schema for the first folder (app_2) which then the second folder (app_1) will have the goto definition jump to the (app_2) file.
