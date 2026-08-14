# Mimas Cards

Card design and card production are separate.

- `design/templates/only-numbers.svg`: default numeric template.
- `design/templates/numbers-and-colors.svg`: number plus five-color symbol template.
- `data/cards.csv`: card production data. If `template_id` is empty, use `only-numbers`.
- `build/template-viewer.html`: local template preview.

Default shape/color set:

| shape_id | symbol | color_id |
|---|---:|---|
| circle | ● | red |
| diamond | ◆ | blue |
| triangle | ▲ | yellow |
| square | ■ | green |
| star | ★ | purple |

The `numbers&colors` template is based on the Google Slides reference deck:

https://docs.google.com/presentation/d/1M7nDAmvPBeXyex0D2j0hKxi5PLaNvWjsRcEuhAL7HaY/edit

The time/clock symbols at the top of the reference slides are intentionally ignored.
