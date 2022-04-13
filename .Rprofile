if (interactive()) {
  if (file.exists("~/.Rprofile")) source("~/.Rprofile")
  library(blogdown)

  options(
    blogdown.hugo.version = "0.95.0",
    blogdown.serve_site.startup = FALSE
  )

  rebuild <- function(..., build_rmd = "timestamp") blogdown::build_site(..., build_rmd = build_rmd)

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
