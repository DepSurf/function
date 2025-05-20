# Function: <code>get_sectorsize</code>

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
In drivers/scsi/sr.c (ffffffff815c0649)
Location: drivers/scsi/sr.c:751
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffff81618df9)
Location: drivers/scsi/sr.c:750
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffff81649a79)
Location: drivers/scsi/sr.c:750
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffff8165e409)
Location: drivers/scsi/sr.c:753
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffff816c7989)
Location: drivers/scsi/sr.c:753
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffff8170435e)
Location: drivers/scsi/sr.c:779
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffff8172711e)
Location: drivers/scsi/sr.c:780
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffff81762854)
Location: drivers/scsi/sr.c:781
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffff81786844)
Location: drivers/scsi/sr.c:781
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void get_sectorsize(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff8184a030)
Location: drivers/scsi/sr.c:828
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
```
**Symbols:**

```
ffffffff8184a030-ffffffff8184a1b9: get_sectorsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_sectorsize(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff8185a6e0)
Location: drivers/scsi/sr.c:800
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff8185a6e0-ffffffff8185a86d: get_sectorsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void get_sectorsize(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff8183d9e0)
Location: drivers/scsi/sr.c:802
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff8183d9e0-ffffffff8183db6a: get_sectorsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void get_sectorsize(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff818ca4a0)
Location: drivers/scsi/sr.c:754
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff818ca4a0-ffffffff818ca62a: get_sectorsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void get_sectorsize(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff81a17980)
Location: drivers/scsi/sr.c:719
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff81a17980-ffffffff81a17b24: get_sectorsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void get_sectorsize(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff81b98890)
Location: drivers/scsi/sr.c:719
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff81b98890-ffffffff81b98a34: get_sectorsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void get_sectorsize(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff81beee30)
Location: drivers/scsi/sr.c:717
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff81beee30-ffffffff81beefe0: get_sectorsize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void get_sectorsize(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff81c445a0)
Location: drivers/scsi/sr.c:718
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff81c445a0-ffffffff81c44750: get_sectorsize (STB_LOCAL)
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
In drivers/scsi/sr.c (ffff80001098d330)
Location: drivers/scsi/sr.c:781
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (c0a5f520)
Location: drivers/scsi/sr.c:781
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (c000000000a4e86c)
Location: drivers/scsi/sr.c:781
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffe0005f11c0)
Location: drivers/scsi/sr.c:781
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffff8173af34)
Location: drivers/scsi/sr.c:781
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffff8171cbd4)
Location: drivers/scsi/sr.c:781
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffff8177b6c4)
Location: drivers/scsi/sr.c:781
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
In drivers/scsi/sr.c (ffffffff817954f4)
Location: drivers/scsi/sr.c:781
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
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
