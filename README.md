# Merger

Image manipulation tool to split **images** into **tiles**.

Inspired by: [pnytko/splitter](https://github.com/pnytko/splitter)

## Requirements

```bash
python3
rich
pillow
```

## Using

If you want to split image into **Squares**.

```bash
python splitter.py --path {path_to_photo} --t_size 16 --out {output_path}
```

If you want to split image into **Rectangles**.

```bash
python splitter.py --path {path_to_photo} --t_size 16x8 --out {output_path}
```

You can also provide a **path** to a folder with **multiple photos** and all files will be processed.

```bash
python splitter.py --path {path_to_folder_with_photos} --t_size 16x8 --out {output_path}
```
