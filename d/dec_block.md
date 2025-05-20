# Function: <code>dec_block</code>

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
In lib/xz/xz_dec_stream.c (ffffffff8140ede2)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (ffffffff81456b02)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (ffffffff814754c2)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (ffffffff8147ebd4)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (ffffffff814ba9f9)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (ffffffff814ed189)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:dec_main
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
In lib/xz/xz_dec_stream.c (ffffffff81500f6d)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (ffffffff8152f364)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (ffffffff815501f4)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum xz_ret dec_block(struct xz_dec *s, struct xz_buf *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xz/xz_dec_stream.c (ffffffff815d9090)
Location: lib/xz/xz_dec_stream.c:218
Inline: False
Direct callers:
  - lib/xz/xz_dec_stream.c:dec_main
```
**Symbols:**

```
ffffffff815d9090-ffffffff815d91fa: dec_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum xz_ret dec_block(struct xz_dec *s, struct xz_buf *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xz/xz_dec_stream.c (ffffffff815f6ce0)
Location: lib/xz/xz_dec_stream.c:218
Inline: False
Direct callers:
  - lib/xz/xz_dec_stream.c:dec_main
```
**Symbols:**

```
ffffffff815f6ce0-ffffffff815f6e4f: dec_block (STB_LOCAL)
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
In lib/xz/xz_dec_stream.c (ffffffff815d9d61)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:dec_main
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum xz_ret dec_block(struct xz_dec *s, struct xz_buf *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xz/xz_dec_stream.c (0)
Location: lib/xz/xz_dec_stream.c:218
Inline: False
Direct callers:
  - lib/xz/xz_dec_stream.c:dec_main
```
**Symbols:**

```
ffffffff81644f70-ffffffff816450f1: dec_block (STB_LOCAL)
ffffffff81cdd557-ffffffff81cdd56c: dec_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum xz_ret dec_block(struct xz_dec *s, struct xz_buf *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xz/xz_dec_stream.c (0)
Location: lib/xz/xz_dec_stream.c:218
Inline: False
Direct callers:
  - lib/xz/xz_dec_stream.c:dec_main
```
**Symbols:**

```
ffffffff8175acb0-ffffffff8175ae47: dec_block (STB_LOCAL)
ffffffff81ea38e6-ffffffff81ea38fb: dec_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum xz_ret dec_block(struct xz_dec *s, struct xz_buf *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xz/xz_dec_stream.c (0)
Location: lib/xz/xz_dec_stream.c:218
Inline: False
Direct callers:
  - lib/xz/xz_dec_stream.c:dec_main
```
**Symbols:**

```
ffffffff81887ff0-ffffffff81888187: dec_block (STB_LOCAL)
ffffffff8208cbc6-ffffffff8208cbdb: dec_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum xz_ret dec_block(struct xz_dec *s, struct xz_buf *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xz/xz_dec_stream.c (0)
Location: lib/xz/xz_dec_stream.c:218
Inline: False
Direct callers:
  - lib/xz/xz_dec_stream.c:dec_main
```
**Symbols:**

```
ffffffff818ca370-ffffffff818ca507: dec_block (STB_LOCAL)
ffffffff8210cf44-ffffffff8210cf59: dec_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum xz_ret dec_block(struct xz_dec *s, struct xz_buf *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xz/xz_dec_stream.c (0)
Location: lib/xz/xz_dec_stream.c:218
Inline: False
Direct callers:
  - lib/xz/xz_dec_stream.c:dec_main
```
**Symbols:**

```
ffffffff8191bf30-ffffffff8191c0c7: dec_block (STB_LOCAL)
ffffffff821eb0b1-ffffffff821eb0c6: dec_block.cold (STB_LOCAL)
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
In lib/xz/xz_dec_stream.c (ffff80001065c19c)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (c0805674)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (c00000000080d7a8)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (ffffffe000489b96)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (ffffffff815487d4)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (ffffffff81538ab4)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (ffffffff81544514)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
In lib/xz/xz_dec_stream.c (ffffffff8155e344)
Location: lib/xz/xz_dec_stream.c:218
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_run
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
