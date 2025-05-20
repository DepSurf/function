# Function: <code>scsi_eh_lock_door</code>

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
In drivers/scsi/scsi_error.c (ffffffff815aca28)
Location: drivers/scsi/scsi_error.c:1968
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff816047ec)
Location: drivers/scsi/scsi_error.c:1968
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81633ece)
Location: drivers/scsi/scsi_error.c:1968
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81648a66)
Location: drivers/scsi/scsi_error.c:1899
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff816b1b70)
Location: drivers/scsi/scsi_error.c:1924
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff816ee044)
Location: drivers/scsi/scsi_error.c:1952
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff81711c30)
Location: drivers/scsi/scsi_error.c:1949
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff8174d0ea)
Location: drivers/scsi/scsi_error.c:1969
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff8177126a)
Location: drivers/scsi/scsi_error.c:1972
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_eh_lock_door(struct scsi_device *sdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81830ca0)
Location: drivers/scsi/scsi_error.c:1974
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_restart_operations
```
**Symbols:**

```
ffffffff81830ca0-ffffffff81830d5a: scsi_eh_lock_door (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_eh_lock_door(struct scsi_device *sdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff818418e0)
Location: drivers/scsi/scsi_error.c:1988
Inline: False
Direct callers:
  - drivers/scsi/scsi_error.c:scsi_restart_operations
```
**Symbols:**

```
ffffffff818418e0-ffffffff8184199a: scsi_eh_lock_door (STB_LOCAL)
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
In drivers/scsi/scsi_error.c (ffffffff81824c93)
Location: drivers/scsi/scsi_error.c:2009
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff818b0513)
Location: drivers/scsi/scsi_error.c:2021
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff819fb5f4)
Location: drivers/scsi/scsi_error.c:2025
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff81b796f4)
Location: drivers/scsi/scsi_error.c:2034
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff81bcd382)
Location: drivers/scsi/scsi_error.c:2079
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff81c21fb2)
Location: drivers/scsi/scsi_error.c:2082
Inline: True
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
In drivers/scsi/scsi_error.c (ffff8000109747d0)
Location: drivers/scsi/scsi_error.c:1972
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (c0a4914c)
Location: drivers/scsi/scsi_error.c:1972
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (c000000000a2e760)
Location: drivers/scsi/scsi_error.c:1972
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffe0005dd14c)
Location: drivers/scsi/scsi_error.c:1972
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff8172595a)
Location: drivers/scsi/scsi_error.c:1972
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff816fed8a)
Location: drivers/scsi/scsi_error.c:1972
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff8176472a)
Location: drivers/scsi/scsi_error.c:1972
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
In drivers/scsi/scsi_error.c (ffffffff8177fdaa)
Location: drivers/scsi/scsi_error.c:1972
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
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
