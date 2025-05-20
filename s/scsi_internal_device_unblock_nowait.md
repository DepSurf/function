# Function: <code>scsi_internal_device_unblock_nowait</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164d990)
Location: drivers/scsi/scsi_lib.c:3069
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff8164d990-ffffffff8164d9f7: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b6c80)
Location: drivers/scsi/scsi_lib.c:3169
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff816b6c80-ffffffff816b6cc7: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816f2f60)
Location: drivers/scsi/scsi_lib.c:3185
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff816f2f60-ffffffff816f2fa7: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81713370)
Location: drivers/scsi/scsi_lib.c:2729
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff81713370-ffffffff817133c1: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174ec50)
Location: drivers/scsi/scsi_lib.c:2678
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff8174ec50-ffffffff8174eca1: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81772e00)
Location: drivers/scsi/scsi_lib.c:2725
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff81772e00-ffffffff81772e5b: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818352d0)
Location: drivers/scsi/scsi_lib.c:2708
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff818352d0-ffffffff8183532b: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81845c00)
Location: drivers/scsi/scsi_lib.c:2714
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff81845c00-ffffffff81845c5b: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81828e90)
Location: drivers/scsi/scsi_lib.c:2731
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff81828e90-ffffffff81828ef5: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b4870)
Location: drivers/scsi/scsi_lib.c:2724
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff818b4870-ffffffff818b48d5: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a013a0)
Location: drivers/scsi/scsi_lib.c:2808
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff81a013a0-ffffffff81a0144d: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7f9a0)
Location: drivers/scsi/scsi_lib.c:2813
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff81b7f9a0-ffffffff81b7fa4d: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd38c0)
Location: drivers/scsi/scsi_lib.c:2830
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff81bd38c0-ffffffff81bd3969: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c28550)
Location: drivers/scsi/scsi_lib.c:2827
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_host_unblock
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff81c28550-ffffffff81c285f9: scsi_internal_device_unblock_nowait (STB_GLOBAL)
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
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010976358)
Location: drivers/scsi/scsi_lib.c:2725
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffff800010976358-ffff8000109763ec: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4acec)
Location: drivers/scsi/scsi_lib.c:2725
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
c0a4acec-c0a4ada4: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a30a70)
Location: drivers/scsi/scsi_lib.c:2725
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
c000000000a30a70-c000000000a30b68: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005dea5e)
Location: drivers/scsi/scsi_lib.c:2725
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffe0005dea5e-ffffffe0005deae2: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817274f0)
Location: drivers/scsi/scsi_lib.c:2725
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff817274f0-ffffffff8172754b: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81700920)
Location: drivers/scsi/scsi_lib.c:2725
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff81700920-ffffffff8170097b: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817662c0)
Location: drivers/scsi/scsi_lib.c:2725
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff817662c0-ffffffff8176631b: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_internal_device_unblock_nowait(struct scsi_device *sdev, enum scsi_device_state new_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81781970)
Location: drivers/scsi/scsi_lib.c:2725
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:device_unblock
```
**Symbols:**

```
ffffffff81781970-ffffffff817819cb: scsi_internal_device_unblock_nowait (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
