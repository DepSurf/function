# Function: <code>io_submit_init_bio</code>

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
In fs/ext4/page-io.c (ffffffff812a0106)
Location: fs/ext4/page-io.c:374
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff812cea95)
Location: fs/ext4/page-io.c:358
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff812e4890)
Location: fs/ext4/page-io.c:358
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff8131e50a)
Location: fs/ext4/page-io.c:368
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff81342b2a)
Location: fs/ext4/page-io.c:369
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff8137094e)
Location: fs/ext4/page-io.c:369
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff81388dd6)
Location: fs/ext4/page-io.c:369
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff813b2eda)
Location: fs/ext4/page-io.c:361
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff813cbf5c)
Location: fs/ext4/page-io.c:361
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_submit_init_bio(struct ext4_io_submit *io, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff814173e0)
Location: fs/ext4/page-io.c:395
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff814173e0-ffffffff814174a3: io_submit_init_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_submit_init_bio(struct ext4_io_submit *io, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8142ade0)
Location: fs/ext4/page-io.c:392
Inline: False
Direct callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8142ade0-ffffffff8142aeb6: io_submit_init_bio (STB_LOCAL)
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
In fs/ext4/page-io.c (ffffffff814326c0)
Location: fs/ext4/page-io.c:392
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff81485f80)
Location: fs/ext4/page-io.c:392
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff815094f8)
Location: fs/ext4/page-io.c:391
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff815a40eb)
Location: fs/ext4/page-io.c:391
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff815dab67)
Location: fs/ext4/page-io.c:391
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/ext4/page-io.c (ffffffff8161338f)
Location: fs/ext4/page-io.c:391
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/ext4/page-io.c (ffff8000104a4114)
Location: fs/ext4/page-io.c:361
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (c0665e68)
Location: fs/ext4/page-io.c:361
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (c0000000005d1300)
Location: fs/ext4/page-io.c:361
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffe000325468)
Location: fs/ext4/page-io.c:361
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff813c453c)
Location: fs/ext4/page-io.c:361
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff813b4fbc)
Location: fs/ext4/page-io.c:361
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff813c19cc)
Location: fs/ext4/page-io.c:361
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/ext4/page-io.c (ffffffff813d6b2c)
Location: fs/ext4/page-io.c:361
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
