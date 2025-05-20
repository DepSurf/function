# Function: <code>iomap_dio_complete_work</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b1080)
Location: fs/iomap.c:652
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff812b1080-ffffffff812b10f5: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812be440)
Location: fs/iomap.c:741
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff812be440-ffffffff812be4b5: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e1de0)
Location: fs/iomap.c:765
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff812e1de0-ffffffff812e1e5a: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130e5c0)
Location: fs/iomap.c:891
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8130e5c0-ffffffff8130e5ee: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81323df0)
Location: fs/iomap.c:1525
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff81323df0-ffffffff81323e1e: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134d510)
Location: fs/iomap/direct-io.c:132
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8134d510-ffffffff8134d53f: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813657d0)
Location: fs/iomap/direct-io.c:128
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff813657d0-ffffffff813657ff: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813adb40)
Location: fs/iomap/direct-io.c:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff813ad880-ffffffff813ad8af: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813bf1b0)
Location: fs/iomap/direct-io.c:135
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff813be400-ffffffff813be42f: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813c62f0)
Location: fs/iomap/direct-io.c:135
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff813c5440-ffffffff813c546f: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8141615e)
Location: fs/iomap/direct-io.c:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff814151e0-ffffffff8141520f: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8148d9f6)
Location: fs/iomap/direct-io.c:139
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8148c840-ffffffff8148c877: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff815211b6)
Location: fs/iomap/direct-io.c:139
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff81520fd0-ffffffff81521007: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff815591e9)
Location: fs/iomap/direct-io.c:133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff81559010-ffffffff81559047: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8158f97f)
Location: fs/iomap/direct-io.c:141
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8158f780-ffffffff8158f7b7: iomap_dio_complete_work (STB_LOCAL)
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
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffff80001042d478)
Location: fs/iomap/direct-io.c:128
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffff80001042d478-ffff80001042d4bc: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c05f5f4c)
Location: fs/iomap/direct-io.c:128
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
c05f5f4c-c05f5f80: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c00000000053db70)
Location: fs/iomap/direct-io.c:128
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
c00000000053db70-c00000000053dbd8: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffe0002c9a5c)
Location: fs/iomap/direct-io.c:128
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffe0002c9a5c-ffffffe0002c9a9c: iomap_dio_complete_work (STB_LOCAL)
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
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135ddb0)
Location: fs/iomap/direct-io.c:128
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8135ddb0-ffffffff8135dddf: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134ea50)
Location: fs/iomap/direct-io.c:128
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8134ea50-ffffffff8134ea7f: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135b880)
Location: fs/iomap/direct-io.c:128
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8135b880-ffffffff8135b8af: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iomap_dio_complete_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8136efd0)
Location: fs/iomap/direct-io.c:128
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
**Symbols:**

```
ffffffff8136efd0-ffffffff8136efff: iomap_dio_complete_work (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
