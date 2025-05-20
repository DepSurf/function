# Function: <code>uni16_to_x8</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff812f7a80)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:__fat_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8132c203)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81341f43)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff813565dd)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8137b201)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff813a9c6f)
Location: fs/fat/dir.c:142
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff813c2a4f)
Location: fs/fat/dir.c:142
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff813ed2ba)
Location: fs/fat/dir.c:143
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff814073da)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uni16_to_x8(struct super_block *sb, unsigned char *ascii, const wchar_t *uni, int len, struct nls_table *nls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81452c20)
Location: fs/fat/dir.c:141
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
**Symbols:**

```
ffffffff81452c20-ffffffff81452d69: uni16_to_x8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uni16_to_x8(struct super_block *sb, unsigned char *ascii, const wchar_t *uni, int len, struct nls_table *nls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8146f0d0)
Location: fs/fat/dir.c:141
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
**Symbols:**

```
ffffffff8146f0d0-ffffffff8146f219: uni16_to_x8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81476ba8)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff814ce2b2)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8155af3a)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff815fb840)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff816337c9)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8166cc99)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffff8000104e6180)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (c06a5a84)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (c0000000006242d8)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffe000358a98)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff813ff9ba)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff813f043a)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff813fcd3a)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8141295a)
Location: fs/fat/dir.c:141
Inline: True
Inline callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/dir.c:fat_search_long
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
