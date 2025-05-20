# Function: <code>__read_end_io</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813cc1d0)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff813cc1d0-ffffffff813cc2df: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff814182b0)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff814182b0-ffffffff814183be: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff8142be10)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff8142be10-ffffffff8142bf1e: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff81432ad0)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff81432ad0-ffffffff81432bde: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff814862a0)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff814862a0-ffffffff814863ae: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff81509b40)
Location: fs/ext4/readpage.c:69
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff81509b40-ffffffff81509d21: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff815a47c0)
Location: fs/ext4/readpage.c:69
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:bio_post_read_processing
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff815a47c0-ffffffff815a48f6: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/readpage.c (0)
Location: fs/ext4/readpage.c:69
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:bio_post_read_processing
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff815db010-ffffffff815db2c5: __read_end_io (STB_LOCAL)
ffffffff820efe37-ffffffff820efe98: __read_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/readpage.c (0)
Location: fs/ext4/readpage.c:69
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:bio_post_read_processing
  - fs/ext4/readpage.c:verity_work
  - fs/ext4/readpage.c:decrypt_work
```
**Symbols:**

```
ffffffff81613970-ffffffff81613b96: __read_end_io (STB_LOCAL)
ffffffff821cd021-ffffffff821cd058: __read_end_io.cold (STB_LOCAL)
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
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffff8000104a45f0)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffff8000104a45f0-ffff8000104a4764: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (c06661d0)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
c06661d0-c0666300: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (c0000000005d1550)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
c0000000005d1550-c0000000005d1748: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffe0003257d4)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffe0003257d4-ffffffe000325906: __read_end_io (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813c47b0)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff813c47b0-ffffffff813c48bf: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813b5230)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff813b5230-ffffffff813b533f: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813c1c40)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff813c1c40-ffffffff813c1d4f: __read_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __read_end_io(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/readpage.c (ffffffff813d6dc0)
Location: fs/ext4/readpage.c:70
Inline: False
Direct callers:
  - fs/ext4/readpage.c:mpage_end_io
  - fs/ext4/readpage.c:verity_work
```
**Symbols:**

```
ffffffff813d6dc0-ffffffff813d6ecf: __read_end_io (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
