# Function: <code>scsi_target_reap_ref_put</code>

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
In drivers/scsi/scsi_scan.c (ffffffff815b359e)
Location: drivers/scsi/scsi_scan.c:394
Inline: True
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
In drivers/scsi/scsi_scan.c (ffffffff8160b9fe)
Location: drivers/scsi/scsi_scan.c:400
Inline: True
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
In drivers/scsi/scsi_scan.c (ffffffff8163b29e)
Location: drivers/scsi/scsi_scan.c:398
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_target_reap_ref_put(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8164e320)
Location: drivers/scsi/scsi_scan.c:400
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffffffff8164e320-ffffffff8164e36b: scsi_target_reap_ref_put (STB_LOCAL)
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
In drivers/scsi/scsi_scan.c (ffffffff816b8c75)
Location: drivers/scsi/scsi_scan.c:401
Inline: True
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
In drivers/scsi/scsi_scan.c (ffffffff816f4fb2)
Location: drivers/scsi/scsi_scan.c:401
Inline: True
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
In drivers/scsi/scsi_scan.c (ffffffff81717912)
Location: drivers/scsi/scsi_scan.c:393
Inline: True
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
In drivers/scsi/scsi_scan.c (ffffffff8175344e)
Location: drivers/scsi/scsi_scan.c:393
Inline: True
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
In drivers/scsi/scsi_scan.c (ffffffff817776ce)
Location: drivers/scsi/scsi_scan.c:393
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8183a5ee)
Location: drivers/scsi/scsi_scan.c:392
Inline: True
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
In drivers/scsi/scsi_scan.c (ffffffff8184afae)
Location: drivers/scsi/scsi_scan.c:392
Inline: True
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
In drivers/scsi/scsi_scan.c (ffffffff8182e30e)
Location: drivers/scsi/scsi_scan.c:410
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
In drivers/scsi/scsi_scan.c (ffffffff818ba0de)
Location: drivers/scsi/scsi_scan.c:416
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
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
In drivers/scsi/scsi_scan.c (ffffffff81a05b01)
Location: drivers/scsi/scsi_scan.c:474
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
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
In drivers/scsi/scsi_scan.c (ffffffff81b84861)
Location: drivers/scsi/scsi_scan.c:474
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
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
In drivers/scsi/scsi_scan.c (ffffffff81bd85d1)
Location: drivers/scsi/scsi_scan.c:474
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
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
In drivers/scsi/scsi_scan.c (ffffffff81c2d2d1)
Location: drivers/scsi/scsi_scan.c:474
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
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
void scsi_target_reap_ref_put(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffff80001097ba68)
Location: drivers/scsi/scsi_scan.c:393
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
ffff80001097ba68-ffff80001097bad8: scsi_target_reap_ref_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_target_reap_ref_put(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c0a4dd1c)
Location: drivers/scsi/scsi_scan.c:393
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_get_host_dev
  - drivers/scsi/scsi_scan.c:__scsi_scan_target
  - drivers/scsi/scsi_scan.c:__scsi_add_device
```
**Symbols:**

```
c0a4dd1c-c0a4dd78: scsi_target_reap_ref_put (STB_LOCAL)
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
In drivers/scsi/scsi_scan.c (c000000000a36e84)
Location: drivers/scsi/scsi_scan.c:393
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
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
In drivers/scsi/scsi_scan.c (ffffffe0005e2d48)
Location: drivers/scsi/scsi_scan.c:393
Inline: True
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
In drivers/scsi/scsi_scan.c (ffffffff8172bdbe)
Location: drivers/scsi/scsi_scan.c:393
Inline: True
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
In drivers/scsi/scsi_scan.c (ffffffff817051de)
Location: drivers/scsi/scsi_scan.c:393
Inline: True
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
In drivers/scsi/scsi_scan.c (ffffffff8176ab8e)
Location: drivers/scsi/scsi_scan.c:393
Inline: True
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
In drivers/scsi/scsi_scan.c (ffffffff817862de)
Location: drivers/scsi/scsi_scan.c:393
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
