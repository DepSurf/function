# Function: <code>scsi_scan</code>

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
In drivers/scsi/scsi_sysfs.c (ffffffff815b5686)
Location: drivers/scsi/scsi_sysfs.c:100
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff8160dda6)
Location: drivers/scsi/scsi_sysfs.c:130
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff8163d646)
Location: drivers/scsi/scsi_sysfs.c:130
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff816520a6)
Location: drivers/scsi/scsi_sysfs.c:130
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff816bb4c6)
Location: drivers/scsi/scsi_sysfs.c:131
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff816f7901)
Location: drivers/scsi/scsi_sysfs.c:131
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff8171a2d1)
Location: drivers/scsi/scsi_sysfs.c:131
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff817559e1)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff81779c61)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_scan(struct Scsi_Host *shost, const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8183cc50)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
```
**Symbols:**

```
ffffffff8183cc50-ffffffff8183cd77: scsi_scan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_scan(struct Scsi_Host *shost, const char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_sysfs.c (ffffffff8184d450)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
```
**Symbols:**

```
ffffffff8184d450-ffffffff8184d577: scsi_scan (STB_LOCAL)
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
In drivers/scsi/scsi_sysfs.c (ffffffff81830955)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff818bc925)
Location: drivers/scsi/scsi_sysfs.c:133
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff81a08ab5)
Location: drivers/scsi/scsi_sysfs.c:133
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff81b87e35)
Location: drivers/scsi/scsi_sysfs.c:133
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff81bdbd25)
Location: drivers/scsi/scsi_sysfs.c:133
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff81c30a55)
Location: drivers/scsi/scsi_sysfs.c:133
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffff80001097eb48)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (c0a52164)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (c000000000a3ac40)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffe0005e558e)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff8172e351)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff81707771)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff8176d121)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
In drivers/scsi/scsi_sysfs.c (ffffffff817888c1)
Location: drivers/scsi/scsi_sysfs.c:132
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_scan
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
