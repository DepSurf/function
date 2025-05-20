# Function: <code>sd_setup_protect_cmnd</code>

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
In drivers/scsi/sd.c (ffffffff815bbdb9)
Location: drivers/scsi/sd.c:596
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffff81614625)
Location: drivers/scsi/sd.c:596
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffff81643fee)
Location: drivers/scsi/sd.c:603
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffff81659ec5)
Location: drivers/scsi/sd.c:653
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffff816c3110)
Location: drivers/scsi/sd.c:661
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffff816ff3b4)
Location: drivers/scsi/sd.c:661
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffff81722177)
Location: drivers/scsi/sd.c:668
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffff8175e476)
Location: drivers/scsi/sd.c:732
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffff8178244e)
Location: drivers/scsi/sd.c:732
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned char sd_setup_protect_cmnd(struct scsi_cmnd *scmd, unsigned int dix, unsigned int dif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81843ba0)
Location: drivers/scsi/sd.c:746
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff81843ba0-ffffffff81843ccb: sd_setup_protect_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned char sd_setup_protect_cmnd(struct scsi_cmnd *scmd, unsigned int dix, unsigned int dif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81853ed0)
Location: drivers/scsi/sd.c:779
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff81853ed0-ffffffff81853ffb: sd_setup_protect_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned char sd_setup_protect_cmnd(struct scsi_cmnd *scmd, unsigned int dix, unsigned int dif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81837900)
Location: drivers/scsi/sd.c:779
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff81837900-ffffffff81837a35: sd_setup_protect_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned char sd_setup_protect_cmnd(struct scsi_cmnd *scmd, unsigned int dix, unsigned int dif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c2ce0)
Location: drivers/scsi/sd.c:778
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff818c2ce0-ffffffff818c2e65: sd_setup_protect_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned char sd_setup_protect_cmnd(struct scsi_cmnd *scmd, unsigned int dix, unsigned int dif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81a0f6d0)
Location: drivers/scsi/sd.c:743
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff81a0f6d0-ffffffff81a0f85f: sd_setup_protect_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned char sd_setup_protect_cmnd(struct scsi_cmnd *scmd, unsigned int dix, unsigned int dif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81b8f8b0)
Location: drivers/scsi/sd.c:743
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff81b8f8b0-ffffffff81b8fa3f: sd_setup_protect_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned char sd_setup_protect_cmnd(struct scsi_cmnd *scmd, unsigned int dix, unsigned int dif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81be5d80)
Location: drivers/scsi/sd.c:745
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff81be5d80-ffffffff81be5f0e: sd_setup_protect_cmnd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned char sd_setup_protect_cmnd(struct scsi_cmnd *scmd, unsigned int dix, unsigned int dif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81c3b1d0)
Location: drivers/scsi/sd.c:785
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
**Symbols:**

```
ffffffff81c3b1d0-ffffffff81c3b35e: sd_setup_protect_cmnd (STB_LOCAL)
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
In drivers/scsi/sd.c (ffff80001098917c)
Location: drivers/scsi/sd.c:732
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (c0a5b134)
Location: drivers/scsi/sd.c:732
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (c000000000a48fa0)
Location: drivers/scsi/sd.c:732
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffe0005ed222)
Location: drivers/scsi/sd.c:732
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffff81736b3e)
Location: drivers/scsi/sd.c:732
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffff817187de)
Location: drivers/scsi/sd.c:732
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffff817772ce)
Location: drivers/scsi/sd.c:732
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
In drivers/scsi/sd.c (ffffffff817910ee)
Location: drivers/scsi/sd.c:732
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
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
