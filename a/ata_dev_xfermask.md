# Function: <code>ata_dev_xfermask</code>

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
In drivers/ata/libata-core.c (ffffffff815ce00a)
Location: drivers/ata/libata-core.c:4397
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff81626bda)
Location: drivers/ata/libata-core.c:4580
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff8165783a)
Location: drivers/ata/libata-core.c:4622
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff8166c04a)
Location: drivers/ata/libata-core.c:4699
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff816d569a)
Location: drivers/ata/libata-core.c:4731
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff8171145a)
Location: drivers/ata/libata-core.c:4737
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff8173390a)
Location: drivers/ata/libata-core.c:4741
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff8176f287)
Location: drivers/ata/libata-core.c:4726
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff817932f7)
Location: drivers/ata/libata-core.c:4726
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ata_dev_xfermask(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4118
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81853840-ffffffff81853b08: ata_dev_xfermask (STB_LOCAL)
ffffffff8185936e-ffffffff818593b2: ata_dev_xfermask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ata_dev_xfermask(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4118
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81863b10-ffffffff81863dd8: ata_dev_xfermask (STB_LOCAL)
ffffffff81c17381-ffffffff81c173c5: ata_dev_xfermask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ata_dev_xfermask(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4118
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81846540-ffffffff8184680f: ata_dev_xfermask (STB_LOCAL)
ffffffff81c08f14-ffffffff81c08f58: ata_dev_xfermask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ata_dev_xfermask(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4178
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff818d3980-ffffffff818d3cad: ata_dev_xfermask (STB_LOCAL)
ffffffff81d0d800-ffffffff81d0d844: ata_dev_xfermask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ata_dev_xfermask(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:4215
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81a24020-ffffffff81a24363: ata_dev_xfermask (STB_LOCAL)
ffffffff81ed6792-ffffffff81ed67dc: ata_dev_xfermask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_dev_xfermask(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba5fd0)
Location: drivers/ata/libata-core.c:4224
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81ba5fd0-ffffffff81ba631e: ata_dev_xfermask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_dev_xfermask(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfca00)
Location: drivers/ata/libata-core.c:4419
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81bfca00-ffffffff81bfcd4c: ata_dev_xfermask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_dev_xfermask(struct ata_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c52470)
Location: drivers/ata/libata-core.c:4418
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
```
**Symbols:**

```
ffffffff81c52470-ffffffff81c527c1: ata_dev_xfermask (STB_LOCAL)
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
In drivers/ata/libata-core.c (ffff80001099d7cc)
Location: drivers/ata/libata-core.c:4726
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (c0a6ddb4)
Location: drivers/ata/libata-core.c:4726
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (c000000000a61630)
Location: drivers/ata/libata-core.c:4726
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffe0005fda1a)
Location: drivers/ata/libata-core.c:4726
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff81758407)
Location: drivers/ata/libata-core.c:4726
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff817382a7)
Location: drivers/ata/libata-core.c:4726
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff81788177)
Location: drivers/ata/libata-core.c:4726
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
In drivers/ata/libata-core.c (ffffffff817a1fc7)
Location: drivers/ata/libata-core.c:4726
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
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
