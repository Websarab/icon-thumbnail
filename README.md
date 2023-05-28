# icon-thumbnail


      data-thumbnail="{% for variant in product.variants %}{% if variant.option1 == value %}{{ variant.metafields.custom.add_your_icon | img_url  }}{% endif %}{% endfor %}"
