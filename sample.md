# ChatGPT Markdown, inside Typora

Typora ChatGPT mirrors the current ChatGPT web Markdown surface: measured spacing, clean system typography, rounded code cards, dotted links, citation pills, blockquotes, task lists, and responsive tables.

> The theme focuses on the Markdown body. It keeps Typora local and lightweight while making long notes read like a familiar ChatGPT answer.

## Research note

与实物资产相对的是金融资产，例如股票和债券。教材强调，这些证券本身可能只是一张纸，甚至只是计算机中的记录，它们并不直接贡献社会生产力。

这句话很容易被误解成“金融资产没用”。不是。它们是人们拥有实物资产收益的凭证，是对实物资产收益或政府收益的索取权。

| 维度 | 实物资产 | 金融资产 |
| --- | --- | --- |
| 本质 | 生产商品和服务的能力 | 对未来收益或现金流的索取权 |
| 是否直接创造社会产出 | 是 | 否 |
| 对个人是否是财富 | 是 | 是 |
| 对整个经济体是否自动增加净财富 | 是 | 不一定，因为一方资产常常是另一方负债 |
| 例子 | 土地、厂房、机器、知识、技术 | 股票、债券、存款、基金份额、租赁凭证 |

## Code card

Inline code keeps the quiet gray pill: `const theme = "typora-chatgpt"`.

```typescript
type Theme = {
  readable: true;
  responsiveTables: true;
  install: "copy one css file";
};
```

## Tasks and citations

Source-like links can be styled as compact pills when Typora markup uses the citation attributes.

- [x] Readable headings and paragraphs
- [x] Rounded code blocks with tuned syntax color
- [x] Tables that wrap or scroll in the right place
- [ ] Copy `typora-chatgpt.css` into the Typora theme folder

## Wide table stress test

| Column | Typography | Spacing | Wrapping | Overflow | Use case |
| --- | --- | --- | --- | --- | --- |
| Desktop | 16px / 26px | ChatGPT-like rhythm | Natural line breaks | Stays inside the content area | Specs, research notes, reports |
| Narrow | Same body style | Safe side padding | Chinese and English text wrap cleanly | Wide tables scroll locally | Small Typora windows |
