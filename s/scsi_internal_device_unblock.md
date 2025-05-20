# Function: <code>scsi_internal_device_unblock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_internal_device_unblock(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815ae140)
Location: drivers/scsi/scsi_lib.c:2997
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff815ae140-ffffffff815ae1de: scsi_internal_device_unblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_internal_device_unblock(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81606010)
Location: drivers/scsi/scsi_lib.c:2871
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff81606010-ffffffff816060ae: scsi_internal_device_unblock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_internal_device_unblock(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81635530)
Location: drivers/scsi/scsi_lib.c:2955
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff81635530-ffffffff816355ce: scsi_internal_device_unblock (STB_GLOBAL)
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
In drivers/scsi/scsi_lib.c (ffffffff8164da0e)
Location: drivers/scsi/scsi_lib.c:3109
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff816b6cde)
Location: drivers/scsi/scsi_lib.c:3214
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff816f2fcb)
Location: drivers/scsi/scsi_lib.c:3230
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff817133eb)
Location: drivers/scsi/scsi_lib.c:2774
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff8174ecc9)
Location: drivers/scsi/scsi_lib.c:2723
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff81772e79)
Location: drivers/scsi/scsi_lib.c:2778
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff81835c9c)
Location: drivers/scsi/scsi_lib.c:2761
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff818467ac)
Location: drivers/scsi/scsi_lib.c:2767
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff81829a1c)
Location: drivers/scsi/scsi_lib.c:2784
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff818b545c)
Location: drivers/scsi/scsi_lib.c:2777
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff81a014dc)
Location: drivers/scsi/scsi_lib.c:2861
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff81b7fafc)
Location: drivers/scsi/scsi_lib.c:2866
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff81bd3a1c)
Location: drivers/scsi/scsi_lib.c:2883
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff81c286ac)
Location: drivers/scsi/scsi_lib.c:2880
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffff800010976418)
Location: drivers/scsi/scsi_lib.c:2778
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (c0a4adc0)
Location: drivers/scsi/scsi_lib.c:2778
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (c000000000a30ba8)
Location: drivers/scsi/scsi_lib.c:2778
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffe0005deb02)
Location: drivers/scsi/scsi_lib.c:2778
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff81727569)
Location: drivers/scsi/scsi_lib.c:2778
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff81700999)
Location: drivers/scsi/scsi_lib.c:2778
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff81766339)
Location: drivers/scsi/scsi_lib.c:2778
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
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
In drivers/scsi/scsi_lib.c (ffffffff817819e9)
Location: drivers/scsi/scsi_lib.c:2778
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
