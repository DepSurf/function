# Function: <code>cis_tpl_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff816cae40)
Location: drivers/mmc/core/sdio_cis.c:111
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
```
**Symbols:**

```
ffffffff816cae40-ffffffff816caf05: cis_tpl_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff8172de00)
Location: drivers/mmc/core/sdio_cis.c:111
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff8172de00-ffffffff8172dec5: cis_tpl_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff81760dc0)
Location: drivers/mmc/core/sdio_cis.c:111
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff81760dc0-ffffffff81760e85: cis_tpl_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff8177f600)
Location: drivers/mmc/core/sdio_cis.c:111
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff8177f600-ffffffff8177f6b2: cis_tpl_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff817f5bb0)
Location: drivers/mmc/core/sdio_cis.c:111
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff817f5bb0-ffffffff817f5c65: cis_tpl_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:111
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff8183f090-ffffffff8183f133: cis_tpl_parse (STB_LOCAL)
ffffffff8183f751-ffffffff8183f770: cis_tpl_parse.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:111
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff8186b040-ffffffff8186b0e3: cis_tpl_parse (STB_LOCAL)
ffffffff8186b701-ffffffff8186b720: cis_tpl_parse.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:107
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff818aef30-ffffffff818aefda: cis_tpl_parse (STB_LOCAL)
ffffffff818af5c8-ffffffff818af5e7: cis_tpl_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:107
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff818e13e0-ffffffff818e148e: cis_tpl_parse (STB_LOCAL)
ffffffff818e1a78-ffffffff818e1a93: cis_tpl_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:107
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff819b44d0-ffffffff819b4573: cis_tpl_parse (STB_LOCAL)
ffffffff819b4b78-ffffffff819b4b93: cis_tpl_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:120
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff819b6af0-ffffffff819b6b93: cis_tpl_parse (STB_LOCAL)
ffffffff81c2b234-ffffffff81c2b24f: cis_tpl_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:120
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff8199b2a0-ffffffff8199b346: cis_tpl_parse (STB_LOCAL)
ffffffff81c1d5c9-ffffffff81c1d5e4: cis_tpl_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:120
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff81a47be0-ffffffff81a47c86: cis_tpl_parse (STB_LOCAL)
ffffffff81d2e6d3-ffffffff81d2e6ee: cis_tpl_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:120
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff81bb5bb0-ffffffff81bb5c6f: cis_tpl_parse (STB_LOCAL)
ffffffff81efab4c-ffffffff81efab67: cis_tpl_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff81d5a4c0)
Location: drivers/mmc/core/sdio_cis.c:120
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff81d5a4c0-ffffffff81d5a590: cis_tpl_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff81dc4e60)
Location: drivers/mmc/core/sdio_cis.c:120
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff81dc4e60-ffffffff81dc4f30: cis_tpl_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff81e7d7a0)
Location: drivers/mmc/core/sdio_cis.c:120
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff81e7d7a0-ffffffff81e7d870: cis_tpl_parse (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffff800010b3b840)
Location: drivers/mmc/core/sdio_cis.c:107
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffff800010b3b840-ffff800010b3b948: cis_tpl_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (c0c1602c)
Location: drivers/mmc/core/sdio_cis.c:107
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
c0c1602c-c0c160f8: cis_tpl_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (c000000000c38410)
Location: drivers/mmc/core/sdio_cis.c:107
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
c000000000c38410-c000000000c385c8: cis_tpl_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffe000712eec)
Location: drivers/mmc/core/sdio_cis.c:107
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffe000712eec-ffffffe000712fac: cis_tpl_parse (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:107
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff81884da0-ffffffff81884e4e: cis_tpl_parse (STB_LOCAL)
ffffffff81885438-ffffffff81885453: cis_tpl_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:107
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff818d6240-ffffffff818d62ee: cis_tpl_parse (STB_LOCAL)
ffffffff818d68d8-ffffffff818d68f3: cis_tpl_parse.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cis_tpl_parse(struct mmc_card *card, struct sdio_func *func, const char *tpl_descr, const struct cis_tpl *tpl, int tpl_count, unsigned char code, const unsigned char *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:107
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_cis
  - drivers/mmc/core/sdio_cis.c:cistpl_funce
```
**Symbols:**

```
ffffffff818f2d60-ffffffff818f2e0e: cis_tpl_parse (STB_LOCAL)
ffffffff818f33f8-ffffffff818f3413: cis_tpl_parse.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
