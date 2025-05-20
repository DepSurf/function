# Function: <code>scsi_queue_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff815a8550)
Location: drivers/scsi/hosts.c:627
Inline: True
```
**Symbols:**

```
ffffffff815a8550-ffffffff815a85a8: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81600400)
Location: drivers/scsi/hosts.c:640
Inline: True
```
**Symbols:**

```
ffffffff81600400-ffffffff81600458: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8162fae0)
Location: drivers/scsi/hosts.c:644
Inline: True
```
**Symbols:**

```
ffffffff8162fae0-ffffffff8162fb38: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81644510)
Location: drivers/scsi/hosts.c:632
Inline: True
```
**Symbols:**

```
ffffffff81644510-ffffffff81644568: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816ad4a0)
Location: drivers/scsi/hosts.c:627
Inline: True
```
**Symbols:**

```
ffffffff816ad4a0-ffffffff816ad4f8: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816e9760)
Location: drivers/scsi/hosts.c:603
Inline: True
```
**Symbols:**

```
ffffffff816e9760-ffffffff816e97b8: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8170d260)
Location: drivers/scsi/hosts.c:600
Inline: True
```
**Symbols:**

```
ffffffff8170d260-ffffffff8170d2b8: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81749128)
Location: drivers/scsi/hosts.c:604
Inline: True
```
**Symbols:**

```
ffffffff81749128-ffffffff8174915c: scsi_queue_work.cold (STB_LOCAL)
ffffffff81748d80-ffffffff81748dab: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8176d278)
Location: drivers/scsi/hosts.c:604
Inline: True
```
**Symbols:**

```
ffffffff8176d278-ffffffff8176d2ac: scsi_queue_work.cold (STB_LOCAL)
ffffffff8176ced0-ffffffff8176cefb: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8182f7b2)
Location: drivers/scsi/hosts.c:621
Inline: True
```
**Symbols:**

```
ffffffff8182f7b2-ffffffff8182f7e6: scsi_queue_work.cold (STB_LOCAL)
ffffffff8182f030-ffffffff8182f05b: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81c162c4)
Location: drivers/scsi/hosts.c:624
Inline: True
```
**Symbols:**

```
ffffffff81c162c4-ffffffff81c162f8: scsi_queue_work.cold (STB_LOCAL)
ffffffff81840050-ffffffff8184007b: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81c07fca)
Location: drivers/scsi/hosts.c:628
Inline: True
```
**Symbols:**

```
ffffffff81c07fca-ffffffff81c07ffe: scsi_queue_work.cold (STB_LOCAL)
ffffffff818232b0-ffffffff818232db: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81d0be49)
Location: drivers/scsi/hosts.c:630
Inline: True
```
**Symbols:**

```
ffffffff81d0be49-ffffffff81d0be7d: scsi_queue_work.cold (STB_LOCAL)
ffffffff818adbd0-ffffffff818adbfb: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81ed4d8d)
Location: drivers/scsi/hosts.c:632
Inline: True
```
**Symbols:**

```
ffffffff81ed4d8d-ffffffff81ed4dc1: scsi_queue_work.cold (STB_LOCAL)
ffffffff819f8a80-ffffffff819f8ab7: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81b76570)
Location: drivers/scsi/hosts.c:647
Inline: True
```
**Symbols:**

```
ffffffff81b76570-ffffffff81b765e0: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81bca1f0)
Location: drivers/scsi/hosts.c:647
Inline: True
```
**Symbols:**

```
ffffffff81bca1f0-ffffffff81bca260: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81c1ee20)
Location: drivers/scsi/hosts.c:647
Inline: True
```
**Symbols:**

```
ffffffff81c1ee20-ffffffff81c1ee90: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffff80001096f1f8)
Location: drivers/scsi/hosts.c:604
Inline: True
```
**Symbols:**

```
ffff80001096f1f8-ffff80001096f264: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c0a44548)
Location: drivers/scsi/hosts.c:604
Inline: True
```
**Symbols:**

```
c0a44548-c0a445a4: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (c000000000a28bb0)
Location: drivers/scsi/hosts.c:604
Inline: True
```
**Symbols:**

```
c000000000a28bb0-c000000000a28c30: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/hosts.c (ffffffe0005d931c)
Location: drivers/scsi/hosts.c:604
Inline: True
```
**Symbols:**

```
ffffffe0005d931c-ffffffe0005d9382: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81721968)
Location: drivers/scsi/hosts.c:604
Inline: True
```
**Symbols:**

```
ffffffff81721968-ffffffff8172199c: scsi_queue_work.cold (STB_LOCAL)
ffffffff817215c0-ffffffff817215eb: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff816fad98)
Location: drivers/scsi/hosts.c:604
Inline: True
Direct callers:
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_add
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_create
```
**Symbols:**

```
ffffffff816fad98-ffffffff816fadcc: scsi_queue_work.cold (STB_LOCAL)
ffffffff816fa9f0-ffffffff816faa1b: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff81760738)
Location: drivers/scsi/hosts.c:604
Inline: True
```
**Symbols:**

```
ffffffff81760738-ffffffff8176076c: scsi_queue_work.cold (STB_LOCAL)
ffffffff81760390-ffffffff817603bb: scsi_queue_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_queue_work(struct Scsi_Host *shost, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/hosts.c (ffffffff8177bd98)
Location: drivers/scsi/hosts.c:604
Inline: True
```
**Symbols:**

```
ffffffff8177bd98-ffffffff8177bdcc: scsi_queue_work.cold (STB_LOCAL)
ffffffff8177b9f0-ffffffff8177ba1b: scsi_queue_work (STB_GLOBAL)
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
