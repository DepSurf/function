# Function: <code>escape_hex</code>

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
In lib/string_helpers.c (ffffffff814013b7)
Location: lib/string_helpers.c:412
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff81448b58)
Location: lib/string_helpers.c:416
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff81467548)
Location: lib/string_helpers.c:416
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff8146cc1f)
Location: lib/string_helpers.c:416
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff81498f3f)
Location: lib/string_helpers.c:416
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff814ce2ba)
Location: lib/string_helpers.c:416
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff814e2baa)
Location: lib/string_helpers.c:416
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff8150e945)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff8152c845)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
  - lib/string_helpers.c:string_escape_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool escape_hex(unsigned char c, char **dst, char *end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81590b54)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
Direct callers:
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:string_escape_mem
```
**Symbols:**

```
ffffffff81590420-ffffffff81590476: escape_hex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool escape_hex(unsigned char c, char **dst, char *end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff815ad6f4)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
Direct callers:
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:string_escape_mem
```
**Symbols:**

```
ffffffff815acf90-ffffffff815acfe6: escape_hex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool escape_hex(unsigned char c, char **dst, char *end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff815b8390)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
Direct callers:
  - lib/string_helpers.c:kstrdup_quotable
  - lib/string_helpers.c:string_escape_mem
```
**Symbols:**

```
ffffffff815b7c40-ffffffff815b7c9b: escape_hex (STB_LOCAL)
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
In lib/string_helpers.c (ffffffff8161ea8b)
Location: lib/string_helpers.c:421
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff816ec946)
Location: lib/string_helpers.c:422
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff817dd1fb)
Location: lib/string_helpers.c:466
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff8181c9a4)
Location: lib/string_helpers.c:466
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff81862754)
Location: lib/string_helpers.c:468
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffff8000106388a0)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (c07de144)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (c0000000007ded80)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffe000465610)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff81524e25)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff81515105)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff81520eb5)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
  - lib/string_helpers.c:string_escape_mem
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
In lib/string_helpers.c (ffffffff8153a835)
Location: lib/string_helpers.c:418
Inline: True
Inline callers:
  - lib/string_helpers.c:string_escape_mem_ascii
  - lib/string_helpers.c:string_escape_mem
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
</ul>
