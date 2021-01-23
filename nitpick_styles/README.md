# Nitpick styles

- Nitpick: https://nitpick.readthedocs.io/en/latest/

Nitpick allows linting your linters configuration, that way we can have
same linters configuration across the entire organization.

`nitpick-*.toml` files include specific configuration for Package/Project/Basic.
It works by including and overriding more generic TOML files for many different tools that
are contained in this folder.
