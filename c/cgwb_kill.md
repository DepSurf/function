# Function: <code>cgwb_kill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811ae230)
Location: mm/backing-dev.c:508
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:bdi_unregister
```
**Symbols:**

```
ffffffff811ae230-ffffffff811ae2f1: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811c75b0)
Location: mm/backing-dev.c:508
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff811c75b0-ffffffff811c765a: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811d76d0)
Location: mm/backing-dev.c:509
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff811d76d0-ffffffff811d777a: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e04a0)
Location: mm/backing-dev.c:525
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff811e04a0-ffffffff811e053b: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f6490)
Location: mm/backing-dev.c:538
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff811f6490-ffffffff811f652b: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81217770)
Location: mm/backing-dev.c:518
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff81217770-ffffffff8121780b: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122a680)
Location: mm/backing-dev.c:519
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff8122a680-ffffffff8122a71b: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (0)
Location: mm/backing-dev.c:506
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff8123a2f0-ffffffff8123a38b: cgwb_kill (STB_LOCAL)
ffffffff8123bd66-ffffffff8123bd79: cgwb_kill.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812485f0)
Location: mm/backing-dev.c:510
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff812485f0-ffffffff8124868b: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812767b0)
Location: mm/backing-dev.c:509
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_bdi_unregister
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff812767b0-ffffffff8127684e: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812810b0)
Location: mm/backing-dev.c:410
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_bdi_unregister
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff812810b0-ffffffff8128114e: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812861e0)
Location: mm/backing-dev.c:409
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff812861e0-ffffffff8128627e: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c5420)
Location: mm/backing-dev.c:430
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff812c5420-ffffffff812c54f0: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81322af0)
Location: mm/backing-dev.c:419
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff81322af0-ffffffff81322bce: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813972b0)
Location: mm/backing-dev.c:546
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff813972b0-ffffffff8139738e: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813ca240)
Location: mm/backing-dev.c:559
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff813ca240-ffffffff813ca31e: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f4bd0)
Location: mm/backing-dev.c:557
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_create
```
**Symbols:**

```
ffffffff813f4bd0-ffffffff813f4cae: cgwb_kill (STB_LOCAL)
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
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102dd660)
Location: mm/backing-dev.c:510
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffff8000102dd660-ffff8000102dd6e8: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c0502b00)
Location: mm/backing-dev.c:510
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
c0502b00-c0502b94: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039ce70)
Location: mm/backing-dev.c:510
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
c00000000039ce70-c00000000039cf34: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f5bc8)
Location: mm/backing-dev.c:510
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffe0001f5bc8-ffffffe0001f5c40: cgwb_kill (STB_LOCAL)
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
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81240c40)
Location: mm/backing-dev.c:510
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff81240c40-ffffffff81240cdb: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81233c40)
Location: mm/backing-dev.c:510
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff81233c40-ffffffff81233cdb: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123e9e0)
Location: mm/backing-dev.c:510
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff8123e9e0-ffffffff8123ea7b: cgwb_kill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgwb_kill(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124e110)
Location: mm/backing-dev.c:510
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:wb_blkcg_offline
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff8124e110-ffffffff8124e1ab: cgwb_kill (STB_LOCAL)
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
