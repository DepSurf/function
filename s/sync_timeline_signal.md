# Function: <code>sync_timeline_signal</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8162c504)
Location: drivers/dma-buf/sw_sync.c:136
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
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
In drivers/dma-buf/sw_sync.c (ffffffff81641ad6)
Location: drivers/dma-buf/sw_sync.c:136
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff816aa8b0)
Location: drivers/dma-buf/sw_sync.c:205
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff816aa8b0-ffffffff816aa9b9: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff816e6e60)
Location: drivers/dma-buf/sw_sync.c:205
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff816e6e60-ffffffff816e6f69: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8170a120)
Location: drivers/dma-buf/sw_sync.c:204
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff8170a120-ffffffff8170a229: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81745940)
Location: drivers/dma-buf/sw_sync.c:195
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81745940-ffffffff81745a61: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81769ac0)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81769ac0-ffffffff81769bdd: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8182bc90)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff8182bc90-ffffffff8182bda3: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8183cd00)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff8183cd00-ffffffff8183ce01: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff81820120)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81820120-ffffffff81820221: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff818aa7e0-ffffffff818aa8fd: sync_timeline_signal (STB_LOCAL)
ffffffff81d0bd81-ffffffff81d0bdab: sync_timeline_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff819f46e0-ffffffff819f4818: sync_timeline_signal (STB_LOCAL)
ffffffff81ed4bb1-ffffffff81ed4bdb: sync_timeline_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81b71b10-ffffffff81b71c48: sync_timeline_signal (STB_LOCAL)
ffffffff8209b923-ffffffff8209b94d: sync_timeline_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81bc56f0-ffffffff81bc5933: sync_timeline_signal (STB_LOCAL)
ffffffff8211c823-ffffffff8211c84e: sync_timeline_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dma-buf/sw_sync.c (0)
Location: drivers/dma-buf/sw_sync.c:230
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff81c1a0d0-ffffffff81c1a313: sync_timeline_signal (STB_LOCAL)
ffffffff821fa6b8-ffffffff821fa6e3: sync_timeline_signal.cold (STB_LOCAL)
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
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffff80001096b310)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffff80001096b310-ffff80001096b4a8: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (c0a40f64)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
c0a40f64-c0a410e8: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (c000000000a23d50)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
c000000000a23d50-c000000000a23f60: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffe0005d6690)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffe0005d6690-ffffffe0005d67e0: sync_timeline_signal (STB_LOCAL)
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
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8171e1b0)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff8171e1b0-ffffffff8171e2cd: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff816f74d0)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff816f74d0-ffffffff816f75e7: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff8175cf80)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff8175cf80-ffffffff8175d09d: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sync_timeline_signal(struct sync_timeline *obj, unsigned int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/sw_sync.c (ffffffff817783b0)
Location: drivers/dma-buf/sw_sync.c:192
Inline: False
Direct callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
```
**Symbols:**

```
ffffffff817783b0-ffffffff817784dd: sync_timeline_signal (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
