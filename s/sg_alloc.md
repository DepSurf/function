# Function: <code>sg_alloc</code>

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
In drivers/scsi/sg.c (ffffffff815c44a5)
Location: drivers/scsi/sg.c:1399
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffff8161ccb5)
Location: drivers/scsi/sg.c:1400
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffff8164d8c5)
Location: drivers/scsi/sg.c:1393
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffff816621c5)
Location: drivers/scsi/sg.c:1412
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffff816cb429)
Location: drivers/scsi/sg.c:1411
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffff81707e34)
Location: drivers/scsi/sg.c:1448
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffff81728f44)
Location: drivers/scsi/sg.c:1439
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffff81764295)
Location: drivers/scsi/sg.c:1434
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffff81788285)
Location: drivers/scsi/sg.c:1434
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
Sg_device *sg_alloc(struct gendisk *disk, struct scsi_device *scsidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8184e0a0)
Location: drivers/scsi/sg.c:1457
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_add_device
```
**Symbols:**

```
ffffffff8184e0a0-ffffffff8184e2b5: sg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
Sg_device *sg_alloc(struct gendisk *disk, struct scsi_device *scsidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8185e650)
Location: drivers/scsi/sg.c:1457
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_add_device
```
**Symbols:**

```
ffffffff8185e650-ffffffff8185e865: sg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
Sg_device *sg_alloc(struct gendisk *disk, struct scsi_device *scsidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81840dd0)
Location: drivers/scsi/sg.c:1456
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_add_device
```
**Symbols:**

```
ffffffff81840dd0-ffffffff81840fe5: sg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
Sg_device *sg_alloc(struct scsi_device *scsidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff818cdaa0)
Location: drivers/scsi/sg.c:1437
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_add_device
```
**Symbols:**

```
ffffffff818cdaa0-ffffffff818cdcac: sg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
Sg_device *sg_alloc(struct scsi_device *scsidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81a1bc50)
Location: drivers/scsi/sg.c:1430
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_add_device
```
**Symbols:**

```
ffffffff81a1bc50-ffffffff81a1be6e: sg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
Sg_device *sg_alloc(struct scsi_device *scsidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81b9ce10)
Location: drivers/scsi/sg.c:1431
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_add_device
```
**Symbols:**

```
ffffffff81b9ce10-ffffffff81b9d02e: sg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
Sg_device *sg_alloc(struct scsi_device *scsidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81bf33f0)
Location: drivers/scsi/sg.c:1432
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_add_device
```
**Symbols:**

```
ffffffff81bf33f0-ffffffff81bf360e: sg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
Sg_device *sg_alloc(struct scsi_device *scsidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81c48ce0)
Location: drivers/scsi/sg.c:1432
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_add_device
```
**Symbols:**

```
ffffffff81c48ce0-ffffffff81c48f2e: sg_alloc (STB_LOCAL)
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
In drivers/scsi/sg.c (ffff800010991610)
Location: drivers/scsi/sg.c:1434
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (c0a61a68)
Location: drivers/scsi/sg.c:1434
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (c000000000a52c9c)
Location: drivers/scsi/sg.c:1434
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffe0005f37c6)
Location: drivers/scsi/sg.c:1434
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffff8173c975)
Location: drivers/scsi/sg.c:1434
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffff8171e615)
Location: drivers/scsi/sg.c:1434
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffff8177d105)
Location: drivers/scsi/sg.c:1434
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
In drivers/scsi/sg.c (ffffffff81796f35)
Location: drivers/scsi/sg.c:1434
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param reordered. </b>
<code>disk, scsidp</code> ➡️ <code>scsidp</code>
</li>
</ul>
</details>
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
