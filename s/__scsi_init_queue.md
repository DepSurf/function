# Function: <code>__scsi_init_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815ada90)
Location: drivers/scsi/scsi_lib.c:2098
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:__scsi_alloc_queue
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff815ada90-ffffffff815adbef: __scsi_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81605990)
Location: drivers/scsi/scsi_lib.c:2014
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/scsi_lib.c:__scsi_alloc_queue
```
**Symbols:**

```
ffffffff81605990-ffffffff81605af0: __scsi_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81634eb0)
Location: drivers/scsi/scsi_lib.c:2032
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/scsi_lib.c:__scsi_alloc_queue
```
**Symbols:**

```
ffffffff81634eb0-ffffffff81635013: __scsi_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81649ca0)
Location: drivers/scsi/scsi_lib.c:2068
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff81649ca0-ffffffff81649e06: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b2df0)
Location: drivers/scsi/scsi_lib.c:2141
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
```
**Symbols:**

```
ffffffff816b2df0-ffffffff816b2f56: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816ef050)
Location: drivers/scsi/scsi_lib.c:2156
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
```
**Symbols:**

```
ffffffff816ef050-ffffffff816ef16b: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81712ab0)
Location: drivers/scsi/scsi_lib.c:1822
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff81712ab0-ffffffff81712bb8: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8174e5a0)
Location: drivers/scsi/scsi_lib.c:1769
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff8174e5a0-ffffffff8174e6e0: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81772750)
Location: drivers/scsi/scsi_lib.c:1782
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff81772750-ffffffff81772890: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81834aa0)
Location: drivers/scsi/scsi_lib.c:1778
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff81834aa0-ffffffff81834be0: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818454e0)
Location: drivers/scsi/scsi_lib.c:1800
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff818454e0-ffffffff81845620: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81828660)
Location: drivers/scsi/scsi_lib.c:1811
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff81828660-ffffffff8182877e: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b3f60)
Location: drivers/scsi/scsi_lib.c:1813
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff818b3f60-ffffffff818b407e: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff819fefa0)
Location: drivers/scsi/scsi_lib.c:1870
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff819fefa0-ffffffff819ff0ca: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7d5a0)
Location: drivers/scsi/scsi_lib.c:1875
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81b7d5a0-ffffffff81b7d6a3: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd1330)
Location: drivers/scsi/scsi_lib.c:1879
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81bd1330-ffffffff81bd1433: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c25fa0)
Location: drivers/scsi/scsi_lib.c:1876
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81c25fa0-ffffffff81c260a3: __scsi_init_queue (STB_GLOBAL)
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
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010975ca0)
Location: drivers/scsi/scsi_lib.c:1782
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffff800010975ca0-ffff800010975db8: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4a578)
Location: drivers/scsi/scsi_lib.c:1782
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
c0a4a578-c0a4a69c: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a2fff0)
Location: drivers/scsi/scsi_lib.c:1782
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
c000000000a2fff0-c000000000a30198: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005de382)
Location: drivers/scsi/scsi_lib.c:1782
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffe0005de382-ffffffe0005de49e: __scsi_init_queue (STB_GLOBAL)
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
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81726e40)
Location: drivers/scsi/scsi_lib.c:1782
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff81726e40-ffffffff81726f80: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81700270)
Location: drivers/scsi/scsi_lib.c:1782
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_create
  - drivers/scsi/scsi_transport_fc.c:fc_host_setup
```
**Symbols:**

```
ffffffff81700270-ffffffff817003b0: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81765c10)
Location: drivers/scsi/scsi_lib.c:1782
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff81765c10-ffffffff81765d50: __scsi_init_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host *shost, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817812a0)
Location: drivers/scsi/scsi_lib.c:1782
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue
```
**Symbols:**

```
ffffffff817812a0-ffffffff817813e0: __scsi_init_queue (STB_GLOBAL)
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
