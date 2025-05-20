# Function: <code>scsi_target_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff815b1a10)
Location: drivers/scsi/scsi_scan.c:311
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
**Symbols:**

```
ffffffff815b1a10-ffffffff815b1ac5: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81609df0)
Location: drivers/scsi/scsi_scan.c:316
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
```
**Symbols:**

```
ffffffff81609df0-ffffffff81609ec3: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816396d0)
Location: drivers/scsi/scsi_scan.c:314
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
```
**Symbols:**

```
ffffffff816396d0-ffffffff816397a3: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8164e240)
Location: drivers/scsi/scsi_scan.c:315
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_put
```
**Symbols:**

```
ffffffff8164e240-ffffffff8164e313: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816b74e0)
Location: drivers/scsi/scsi_scan.c:316
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
```
**Symbols:**

```
ffffffff816b74e0-ffffffff816b75b6: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff816f37e0)
Location: drivers/scsi/scsi_scan.c:316
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
```
**Symbols:**

```
ffffffff816f37e0-ffffffff816f38b3: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff817161e0)
Location: drivers/scsi/scsi_scan.c:308
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
```
**Symbols:**

```
ffffffff817161e0-ffffffff8171629a: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff817519c0)
Location: drivers/scsi/scsi_scan.c:308
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
```
**Symbols:**

```
ffffffff817519c0-ffffffff81751a7b: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81775c40)
Location: drivers/scsi/scsi_scan.c:308
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
```
**Symbols:**

```
ffffffff81775c40-ffffffff81775cfe: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81839220)
Location: drivers/scsi/scsi_scan.c:307
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
**Symbols:**

```
ffffffff81839220-ffffffff818392de: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81849aa0)
Location: drivers/scsi/scsi_scan.c:307
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
**Symbols:**

```
ffffffff81849aa0-ffffffff81849b5e: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8182ced0)
Location: drivers/scsi/scsi_scan.c:325
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
**Symbols:**

```
ffffffff8182ced0-ffffffff8182cf8e: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff818b8c70)
Location: drivers/scsi/scsi_scan.c:331
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
**Symbols:**

```
ffffffff818b8c70-ffffffff818b8d2e: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81a04540)
Location: drivers/scsi/scsi_scan.c:389
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
**Symbols:**

```
ffffffff81a04540-ffffffff81a04610: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81b83150)
Location: drivers/scsi/scsi_scan.c:389
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
**Symbols:**

```
ffffffff81b83150-ffffffff81b83220: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81bd6e80)
Location: drivers/scsi/scsi_scan.c:389
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
**Symbols:**

```
ffffffff81bd6e80-ffffffff81bd6f50: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81c2bb20)
Location: drivers/scsi/scsi_scan.c:389
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
**Symbols:**

```
ffffffff81c2bb20-ffffffff81c2bbf0: scsi_target_destroy (STB_LOCAL)
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
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffff80001097b948)
Location: drivers/scsi/scsi_scan.c:308
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_put
```
**Symbols:**

```
ffff80001097b948-ffff80001097ba64: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c0a4dc60)
Location: drivers/scsi/scsi_scan.c:308
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_put
```
**Symbols:**

```
c0a4dc60-c0a4dd1c: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (c000000000a34b70)
Location: drivers/scsi/scsi_scan.c:308
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_scan.c:scsi_target_reap
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
**Symbols:**

```
c000000000a34b70-c000000000a34c84: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffe0005e151a)
Location: drivers/scsi/scsi_scan.c:308
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
```
**Symbols:**

```
ffffffe0005e151a-ffffffe0005e15c2: scsi_target_destroy (STB_LOCAL)
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
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff8172a330)
Location: drivers/scsi/scsi_scan.c:308
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
```
**Symbols:**

```
ffffffff8172a330-ffffffff8172a3ee: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81703750)
Location: drivers/scsi/scsi_scan.c:308
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
```
**Symbols:**

```
ffffffff81703750-ffffffff8170380e: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81769100)
Location: drivers/scsi/scsi_scan.c:308
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
```
**Symbols:**

```
ffffffff81769100-ffffffff817691be: scsi_target_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_target_destroy(struct scsi_target *starget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_scan.c (ffffffff81784870)
Location: drivers/scsi/scsi_scan.c:308
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_target
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
  - drivers/scsi/scsi_scan.c:scsi_target_reap_ref_release
```
**Symbols:**

```
ffffffff81784870-ffffffff8178492e: scsi_target_destroy (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
