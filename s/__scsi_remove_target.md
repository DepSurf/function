# Function: <code>__scsi_remove_target</code>

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
In drivers/scsi/scsi_sysfs.c (ffffffff815b5d9a)
Location: drivers/scsi/scsi_sysfs.c:1162
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff8160e4a1)
Location: drivers/scsi/scsi_sysfs.c:1337
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff8163dd41)
Location: drivers/scsi/scsi_sysfs.c:1333
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff816528ea)
Location: drivers/scsi/scsi_sysfs.c:1357
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff816bbce0)
Location: drivers/scsi/scsi_sysfs.c:1402
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff816f81a0)
Location: drivers/scsi/scsi_sysfs.c:1425
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff8171aa9c)
Location: drivers/scsi/scsi_sysfs.c:1431
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff81756176)
Location: drivers/scsi/scsi_sysfs.c:1443
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff8177a416)
Location: drivers/scsi/scsi_sysfs.c:1452
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __scsi_remove_target(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8183d3d0)
Location: drivers/scsi/scsi_sysfs.c:1472
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
**Symbols:**

```
ffffffff8183d3d0-ffffffff8183d4e7: __scsi_remove_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __scsi_remove_target(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8184dbd0)
Location: drivers/scsi/scsi_sysfs.c:1483
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
```
**Symbols:**

```
ffffffff8184dbd0-ffffffff8184dce7: __scsi_remove_target (STB_LOCAL)
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
In drivers/scsi/scsi_sysfs.c (ffffffff81831161)
Location: drivers/scsi/scsi_sysfs.c:1489
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff818bd1b1)
Location: drivers/scsi/scsi_sysfs.c:1515
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff81a09377)
Location: drivers/scsi/scsi_sysfs.c:1509
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff81b887e7)
Location: drivers/scsi/scsi_sysfs.c:1504
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff81bdc6c7)
Location: drivers/scsi/scsi_sysfs.c:1534
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff81c313f7)
Location: drivers/scsi/scsi_sysfs.c:1534
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffff80001097fb68)
Location: drivers/scsi/scsi_sysfs.c:1452
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (c0a52910)
Location: drivers/scsi/scsi_sysfs.c:1452
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (c000000000a3b7d0)
Location: drivers/scsi/scsi_sysfs.c:1452
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffe0005e5d34)
Location: drivers/scsi/scsi_sysfs.c:1452
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff8172eb06)
Location: drivers/scsi/scsi_sysfs.c:1452
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff81707f26)
Location: drivers/scsi/scsi_sysfs.c:1452
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff8176d8d6)
Location: drivers/scsi/scsi_sysfs.c:1452
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
In drivers/scsi/scsi_sysfs.c (ffffffff81789076)
Location: drivers/scsi/scsi_sysfs.c:1452
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_remove_target
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
