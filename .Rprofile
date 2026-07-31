source("renv/activate.R")

require(quartopost, quietly = T)

if ("author" %in% names(yaml::read_yaml(here::here("_quarto.yml")))) {
  options(
    quartopost.author = yaml::read_yaml(here::here("_quarto.yml"))$author
  )
}

options(
  servr.daemon = TRUE,
  quartopost.verbose = FALSE,              # default = TRUE
  quartopost.draft = FALSE,                # default = TRUE
  quartopost.show_empty_fields = FALSE     # default = TRUE
)

