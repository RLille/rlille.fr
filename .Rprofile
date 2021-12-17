if (interactive()) {
  library(blogdown)

  options(
    blogdown.hugo.version = "0.90.1",
    blogdown.serve_site.startup = FALSE
  )

  rebuild <- function(...) blogdown::build_site(..., local = TRUE, build_rmd = "timestamp")

  update <- function() {
    install_theme(
      theme = "calintat/minimal",
      hostname = "github.com",
      theme_example = FALSE,
      update_config = TRUE,
      force = TRUE,
      update_hugo = TRUE
    )
  }
}
