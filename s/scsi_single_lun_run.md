# Function: <code>scsi_single_lun_run</code>

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
In drivers/scsi/scsi_lib.c (ffffffff815ad57d)
Location: drivers/scsi/scsi_lib.c:344
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff816054c7)
Location: drivers/scsi/scsi_lib.c:310
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff816349e7)
Location: drivers/scsi/scsi_lib.c:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81649a44)
Location: drivers/scsi/scsi_lib.c:348
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff816b2c64)
Location: drivers/scsi/scsi_lib.c:373
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff816eed9d)
Location: drivers/scsi/scsi_lib.c:386
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81712904)
Location: drivers/scsi/scsi_lib.c:375
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff8174e27a)
Location: drivers/scsi/scsi_lib.c:372
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff8177242a)
Location: drivers/scsi/scsi_lib.c:372
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_single_lun_run(struct scsi_device *current_sdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81834790)
Location: drivers/scsi/scsi_lib.c:361
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff81834790-ffffffff81834880: scsi_single_lun_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_single_lun_run(struct scsi_device *current_sdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81845170)
Location: drivers/scsi/scsi_lib.c:346
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff81845170-ffffffff81845260: scsi_single_lun_run (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff818284de)
Location: drivers/scsi/scsi_lib.c:313
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff818b3e1e)
Location: drivers/scsi/scsi_lib.c:318
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff819fee0d)
Location: drivers/scsi/scsi_lib.c:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81b7d456)
Location: drivers/scsi/scsi_lib.c:329
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81bd11e1)
Location: drivers/scsi/scsi_lib.c:327
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81c25e43)
Location: drivers/scsi/scsi_lib.c:324
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffff800010977618)
Location: drivers/scsi/scsi_lib.c:372
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (c0a4a1b8)
Location: drivers/scsi/scsi_lib.c:372
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (c000000000a2fb30)
Location: drivers/scsi/scsi_lib.c:372
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffe0005de0e4)
Location: drivers/scsi/scsi_lib.c:372
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81726b1a)
Location: drivers/scsi/scsi_lib.c:372
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff816fff4a)
Location: drivers/scsi/scsi_lib.c:372
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff817658ea)
Location: drivers/scsi/scsi_lib.c:372
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81780f7a)
Location: drivers/scsi/scsi_lib.c:372
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
