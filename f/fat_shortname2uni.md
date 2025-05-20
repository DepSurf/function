# Function: <code>fat_shortname2uni</code>

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
In fs/fat/dir.c (ffffffff812f75d7)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff8132ac9d)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff813409dc)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff8135560f)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff8137a232)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff813a8d13)
Location: fs/fat/dir.c:235
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff813c1af3)
Location: fs/fat/dir.c:235
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff813ec32f)
Location: fs/fat/dir.c:236
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff8140644f)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fat_shortname2uni(struct nls_table *nls, unsigned char *buf, int buf_size, wchar_t *uni_buf, short unsigned int opt, int lower);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81453790)
Location: fs/fat/dir.c:234
Inline: True
Direct callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
**Symbols:**

```
ffffffff81453790-ffffffff81453861: fat_shortname2uni (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fat_shortname2uni(struct nls_table *nls, unsigned char *buf, int buf_size, wchar_t *uni_buf, short unsigned int opt, int lower);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8146fc40)
Location: fs/fat/dir.c:234
Inline: True
Direct callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
**Symbols:**

```
ffffffff8146fc40-ffffffff8146fd11: fat_shortname2uni (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fat_shortname2uni(struct nls_table *nls, unsigned char *buf, int buf_size, wchar_t *uni_buf, short unsigned int opt, int lower);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81475100)
Location: fs/fat/dir.c:234
Inline: True
Direct callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
**Symbols:**

```
ffffffff81475100-ffffffff814751d1: fat_shortname2uni (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fat_shortname2uni(struct nls_table *nls, unsigned char *buf, int buf_size, wchar_t *uni_buf, short unsigned int opt, int lower);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff814cbb20)
Location: fs/fat/dir.c:234
Inline: True
Direct callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
```
**Symbols:**

```
ffffffff814cbb20-ffffffff814cbbf1: fat_shortname2uni (STB_LOCAL)
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
In fs/fat/dir.c (ffffffff815584d6)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff815fa506)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff81632466)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff8166b936)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffff8000104e52d0)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (c06a4b90)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (c000000000622f44)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffe0003584ca)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff813fea2f)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff813ef4af)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff813fbdaf)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
In fs/fat/dir.c (ffffffff814119cf)
Location: fs/fat/dir.c:234
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
  - fs/fat/dir.c:fat_parse_short
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
