# Function: <code>tpk_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpk_printk(const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/ttyprintk.c (ffffffff81515700)
Location: drivers/char/ttyprintk.c:43
Inline: False
Direct callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
```
**Symbols:**

```
ffffffff81515700-ffffffff81515881: tpk_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpk_printk(const unsigned char *buf, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/ttyprintk.c (ffffffff81568360)
Location: drivers/char/ttyprintk.c:43
Inline: False
Direct callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
```
**Symbols:**

```
ffffffff81568360-ffffffff815684ed: tpk_printk (STB_LOCAL)
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
In drivers/char/ttyprintk.c (ffffffff81594ac6)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffff815a8bd2)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffff8160f4d2)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffff81649312)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffff81667612)
Location: drivers/char/ttyprintk.c:55
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffff8169d0b2)
Location: drivers/char/ttyprintk.c:52
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffff816bfe1c)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/ttyprintk.c (ffffffff81773d69)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/ttyprintk.c (ffffffff8178ec29)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffff81771a19)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffff817f7600)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
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
In drivers/char/ttyprintk.c (ffffffff81935b03)
Location: drivers/char/ttyprintk.c:54
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
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
In drivers/char/ttyprintk.c (ffffffff81a9587d)
Location: drivers/char/ttyprintk.c:54
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
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
In drivers/char/ttyprintk.c (ffffffff81ae109d)
Location: drivers/char/ttyprintk.c:54
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
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
In drivers/char/ttyprintk.c (ffffffff81b3449d)
Location: drivers/char/ttyprintk.c:54
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
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
In drivers/char/ttyprintk.c (ffff8000108b1e4c)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (c09ac9fc)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (c00000000094a8c0)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffe000564292)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffff8168586c)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffff8166350c)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffff816b3c5c)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
In drivers/char/ttyprintk.c (ffffffff816ce1bc)
Location: drivers/char/ttyprintk.c:53
Inline: True
Inline callers:
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_write
  - drivers/char/ttyprintk.c:tpk_close
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
</ul>
