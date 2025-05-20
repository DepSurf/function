# Function: <code>sg_check_file_access</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81707430)
Location: drivers/scsi/sg.c:225
Inline: True
```
**Symbols:**

```
ffffffff81707430-ffffffff817074ed: sg_check_file_access.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81729f70)
Location: drivers/scsi/sg.c:225
Inline: True
```
**Symbols:**

```
ffffffff81729f70-ffffffff8172a02d: sg_check_file_access.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81765650)
Location: drivers/scsi/sg.c:220
Inline: True
```
**Symbols:**

```
ffffffff81765650-ffffffff8176570d: sg_check_file_access.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81789640)
Location: drivers/scsi/sg.c:220
Inline: True
```
**Symbols:**

```
ffffffff81789640-ffffffff817896fd: sg_check_file_access.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8184d490)
Location: drivers/scsi/sg.c:220
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff8184d490-ffffffff8184d54d: sg_check_file_access.isra.0 (STB_LOCAL)
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
In drivers/scsi/sg.c (ffffffff8185ed13)
Location: drivers/scsi/sg.c:220
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
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
In drivers/scsi/sg.c (ffffffff81842ce3)
Location: drivers/scsi/sg.c:220
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff818cfc83)
Location: drivers/scsi/sg.c:220
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_read
Direct callers:
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff818cd020-ffffffff818cd08f: sg_check_file_access.part.0 (STB_LOCAL)
ffffffff81d0d326-ffffffff81d0d33a: sg_check_file_access.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81a1cfda)
Location: drivers/scsi/sg.c:224
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
Direct callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff81a1ad60-ffffffff81a1adeb: sg_check_file_access.part.0 (STB_LOCAL)
ffffffff81ed62aa-ffffffff81ed62bf: sg_check_file_access.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81b9e2aa)
Location: drivers/scsi/sg.c:224
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
Direct callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff81b9bf60-ffffffff81b9bfeb: sg_check_file_access.part.0 (STB_LOCAL)
ffffffff8209c417-ffffffff8209c42c: sg_check_file_access.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81bf48ca)
Location: drivers/scsi/sg.c:224
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
Direct callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff81bf2550-ffffffff81bf25db: sg_check_file_access.part.0 (STB_LOCAL)
ffffffff8211d350-ffffffff8211d365: sg_check_file_access.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81c4a20a)
Location: drivers/scsi/sg.c:224
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
Direct callers:
  - drivers/scsi/sg.c:sg_write
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff81c47e40-ffffffff81c47ecb: sg_check_file_access.part.0 (STB_LOCAL)
ffffffff821fb388-ffffffff821fb39d: sg_check_file_access.part.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffff80001098eef8)
Location: drivers/scsi/sg.c:220
Inline: True
```
**Symbols:**

```
ffff80001098eef8-ffff80001098efd8: sg_check_file_access.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sg_check_file_access(struct file *filp, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (c0a61900)
Location: drivers/scsi/sg.c:220
Inline: False
```
**Symbols:**

```
c0a61900-c0a619f8: sg_check_file_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sg_check_file_access(struct file *filp, const char *caller);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (c000000000a52ac0)
Location: drivers/scsi/sg.c:220
Inline: True
```
**Symbols:**

```
c000000000a52ac0-c000000000a52bf4: sg_check_file_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sg_check_file_access(struct file *filp, const char *caller);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffe0005f45d2)
Location: drivers/scsi/sg.c:220
Inline: True
```
**Symbols:**

```
ffffffe0005f45d2-ffffffe0005f468c: sg_check_file_access (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8173dd30)
Location: drivers/scsi/sg.c:220
Inline: True
```
**Symbols:**

```
ffffffff8173dd30-ffffffff8173dded: sg_check_file_access.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8171f9d0)
Location: drivers/scsi/sg.c:220
Inline: True
```
**Symbols:**

```
ffffffff8171f9d0-ffffffff8171fa8d: sg_check_file_access.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8177e4c0)
Location: drivers/scsi/sg.c:220
Inline: True
```
**Symbols:**

```
ffffffff8177e4c0-ffffffff8177e57d: sg_check_file_access.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff817982d0)
Location: drivers/scsi/sg.c:220
Inline: True
```
**Symbols:**

```
ffffffff817982d0-ffffffff8179838d: sg_check_file_access.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
