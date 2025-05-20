# Function: <code>start_bunzip</code>

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
In lib/decompress_bunzip2.c (ffffffff81f9c688)
Location: lib/decompress_bunzip2.c:628
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff81fc7a0a)
Location: lib/decompress_bunzip2.c:628
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff82004963)
Location: lib/decompress_bunzip2.c:628
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff8210faaa)
Location: lib/decompress_bunzip2.c:628
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff82719ea4)
Location: lib/decompress_bunzip2.c:628
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff827446ae)
Location: lib/decompress_bunzip2.c:628
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff828fe9cf)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff8291b616)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff829254ae)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int start_bunzip(struct bunzip_data **bdp, void *inbuf, long int len, long int (*fill)(void *, long unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_bunzip2.c (ffffffff82d0b234)
Location: lib/decompress_bunzip2.c:629
Inline: False
Direct callers:
  - lib/decompress_bunzip2.c:bunzip2
```
**Symbols:**

```
ffffffff82d0b234-ffffffff82d0b32f: start_bunzip (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int start_bunzip(struct bunzip_data **bdp, void *inbuf, long int len, long int (*fill)(void *, long unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_bunzip2.c (ffffffff82ff8828)
Location: lib/decompress_bunzip2.c:629
Inline: False
Direct callers:
  - lib/decompress_bunzip2.c:bunzip2
```
**Symbols:**

```
ffffffff82ff8828-ffffffff82ff8921: start_bunzip (STB_LOCAL)
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
In lib/decompress_bunzip2.c (ffffffff8320353c)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff832eb122)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff834a2ada)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff83f18eb7)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff8373f777)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff839741c6)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffff8000114b666c)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (c15bbb24)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (c0000000013c8c68)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffe000045360)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff8290a1b2)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff82902500)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff8291fafc)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
In lib/decompress_bunzip2.c (ffffffff82926520)
Location: lib/decompress_bunzip2.c:629
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
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
