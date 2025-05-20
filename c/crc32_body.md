# Function: <code>crc32_body</code>

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
In lib/crc32.c (ffffffff81406a01)
Location: lib/crc32.c:57
Inline: True
Inline callers:
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_be
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffff8144e642)
Location: lib/crc32.c:57
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffff8146d002)
Location: lib/crc32.c:57
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffff814726f2)
Location: lib/crc32.c:57
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffff8149ee42)
Location: lib/crc32.c:57
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffff814d4094)
Location: lib/crc32.c:57
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffff814e8ae4)
Location: lib/crc32.c:58
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffff81515794)
Location: lib/crc32.c:58
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffff815361d4)
Location: lib/crc32.c:58
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 crc32_body(u32 crc, const unsigned char *buf, size_t len, const u32[256] *tab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff8159a820)
Location: lib/crc32.c:58
Inline: False
Direct callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
```
**Symbols:**

```
ffffffff8159a820-ffffffff8159a90e: crc32_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 crc32_body(u32 crc, const unsigned char *buf, size_t len, const u32[256] *tab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff815b6210)
Location: lib/crc32.c:58
Inline: False
Direct callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
```
**Symbols:**

```
ffffffff815b6210-ffffffff815b62fe: crc32_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 crc32_body(u32 crc, const unsigned char *buf, size_t len, const u32[256] *tab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff815c1050)
Location: lib/crc32.c:58
Inline: False
Direct callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
```
**Symbols:**

```
ffffffff815c1050-ffffffff815c114e: crc32_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 crc32_body(u32 crc, const unsigned char *buf, size_t len, const u32[256] *tab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff81628ec0)
Location: lib/crc32.c:58
Inline: False
Direct callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
```
**Symbols:**

```
ffffffff81628ec0-ffffffff81628fbe: crc32_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 crc32_body(u32 crc, const unsigned char *buf, size_t len, const u32[256] *tab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff816f9d00)
Location: lib/crc32.c:58
Inline: False
Direct callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
```
**Symbols:**

```
ffffffff816f9d00-ffffffff816f9e58: crc32_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 crc32_body(u32 crc, const unsigned char *buf, size_t len, const u32[256] *tab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff817ec670)
Location: lib/crc32.c:58
Inline: False
Direct callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
```
**Symbols:**

```
ffffffff817ec670-ffffffff817ec7c8: crc32_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 crc32_body(u32 crc, const unsigned char *buf, size_t len, const u32[256] *tab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff8182c870)
Location: lib/crc32.c:58
Inline: False
Direct callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
```
**Symbols:**

```
ffffffff8182c870-ffffffff8182c9c0: crc32_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 crc32_body(u32 crc, const unsigned char *buf, size_t len, const u32[256] *tab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crc32.c (ffffffff8187e400)
Location: lib/crc32.c:58
Inline: False
Direct callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
```
**Symbols:**

```
ffffffff8187e400-ffffffff8187e550: crc32_body (STB_LOCAL)
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
In lib/crc32.c (ffff800010642bc4)
Location: lib/crc32.c:58
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (c07e85f4)
Location: lib/crc32.c:58
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (c0000000007edaec)
Location: lib/crc32.c:58
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffe00046ef20)
Location: lib/crc32.c:58
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffff8152e7b4)
Location: lib/crc32.c:58
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffff8151ea94)
Location: lib/crc32.c:58
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffff8152a454)
Location: lib/crc32.c:58
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
In lib/crc32.c (ffffffff81544254)
Location: lib/crc32.c:58
Inline: True
Inline callers:
  - lib/crc32.c:crc32_be
  - lib/crc32.c:__crc32c_le
  - lib/crc32.c:crc32_le
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
