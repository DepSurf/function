# Function: <code>scsi_target_reap_ref_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_target_reap_ref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff815b1ad0)
Location: drivers/scsi/scsi_scan.c:377
Inline: False
```
**Symbols:**

```
ffffffff815b1ad0-ffffffff815b1b0a: scsi_target_reap_ref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_target_reap_ref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81609ed0)
Location: drivers/scsi/scsi_scan.c:383
Inline: False
```
**Symbols:**

```
ffffffff81609ed0-ffffffff81609f0a: scsi_target_reap_ref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_target_reap_ref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816397b0)
Location: drivers/scsi/scsi_scan.c:381
Inline: False
```
**Symbols:**

```
ffffffff816397b0-ffffffff816397ea: scsi_target_reap_ref_release (STB_LOCAL)
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
In drivers/scsi/scsi_scan.c (ffffffff8164e337)
Location: drivers/scsi/scsi_scan.c:382
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_target_reap_ref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816b75c0)
Location: drivers/scsi/scsi_scan.c:383
Inline: False
```
**Symbols:**

```
ffffffff816b75c0-ffffffff816b7601: scsi_target_reap_ref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_target_reap_ref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816f38c0)
Location: drivers/scsi/scsi_scan.c:383
Inline: False
```
**Symbols:**

```
ffffffff816f38c0-ffffffff816f390e: scsi_target_reap_ref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_target_reap_ref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff817162a0)
Location: drivers/scsi/scsi_scan.c:375
Inline: False
```
**Symbols:**

```
ffffffff817162a0-ffffffff817162ee: scsi_target_reap_ref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_target_reap_ref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81751a80)
Location: drivers/scsi/scsi_scan.c:375
Inline: False
```
**Symbols:**

```
ffffffff81751a80-ffffffff81751ad4: scsi_target_reap_ref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_target_reap_ref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81775d00)
Location: drivers/scsi/scsi_scan.c:375
Inline: False
```
**Symbols:**

```
ffffffff81775d00-ffffffff81775d54: scsi_target_reap_ref_release (STB_LOCAL)
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
In drivers/scsi/scsi_scan.c (ffffffff8183a60e)
Location: drivers/scsi/scsi_scan.c:374
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
In drivers/scsi/scsi_scan.c (ffffffff8184afce)
Location: drivers/scsi/scsi_scan.c:374
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
In drivers/scsi/scsi_scan.c (ffffffff8182e32e)
Location: drivers/scsi/scsi_scan.c:392
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
In drivers/scsi/scsi_scan.c (ffffffff818ba0fe)
Location: drivers/scsi/scsi_scan.c:398
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
In drivers/scsi/scsi_scan.c (ffffffff81a05b28)
Location: drivers/scsi/scsi_scan.c:456
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
In drivers/scsi/scsi_scan.c (ffffffff81b84888)
Location: drivers/scsi/scsi_scan.c:456
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
In drivers/scsi/scsi_scan.c (ffffffff81bd85f8)
Location: drivers/scsi/scsi_scan.c:456
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
In drivers/scsi/scsi_scan.c (ffffffff81c2d2f8)
Location: drivers/scsi/scsi_scan.c:456
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffff80001097ba9c)
Location: drivers/scsi/scsi_scan.c:375
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_put
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
In drivers/scsi/scsi_scan.c (c0a4dd44)
Location: drivers/scsi/scsi_scan.c:375
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_put
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
In drivers/scsi/scsi_scan.c (c000000000a36ebc)
Location: drivers/scsi/scsi_scan.c:375
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
In drivers/scsi/scsi_scan.c (ffffffe0005e2d66)
Location: drivers/scsi/scsi_scan.c:375
Inline: True
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
void scsi_target_reap_ref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8172a3f0)
Location: drivers/scsi/scsi_scan.c:375
Inline: False
```
**Symbols:**

```
ffffffff8172a3f0-ffffffff8172a444: scsi_target_reap_ref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_target_reap_ref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81703810)
Location: drivers/scsi/scsi_scan.c:375
Inline: False
```
**Symbols:**

```
ffffffff81703810-ffffffff81703864: scsi_target_reap_ref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_target_reap_ref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff817691c0)
Location: drivers/scsi/scsi_scan.c:375
Inline: False
```
**Symbols:**

```
ffffffff817691c0-ffffffff81769214: scsi_target_reap_ref_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_target_reap_ref_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81784930)
Location: drivers/scsi/scsi_scan.c:375
Inline: False
```
**Symbols:**

```
ffffffff81784930-ffffffff81784984: scsi_target_reap_ref_release (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
