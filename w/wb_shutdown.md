# Function: <code>wb_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811ae170)
Location: mm/backing-dev.c:342
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:bdi_unregister
```
**Symbols:**

```
ffffffff811ae170-ffffffff811ae1f3: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811c7db0)
Location: mm/backing-dev.c:342
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff811c7db0-ffffffff811c7e34: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811d7ed0)
Location: mm/backing-dev.c:343
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff811d7ed0-ffffffff811d7f54: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e0ab0)
Location: mm/backing-dev.c:353
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff811e0ab0-ffffffff811e0bb1: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f6aa0)
Location: mm/backing-dev.c:366
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff811f6aa0-ffffffff811f6ba1: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81217d70)
Location: mm/backing-dev.c:356
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff81217d70-ffffffff81217e31: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122af20)
Location: mm/backing-dev.c:356
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff8122af20-ffffffff8122afe1: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff8123bd79)
Location: mm/backing-dev.c:343
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff8123a8f0-ffffffff8123a9b1: wb_shutdown (STB_LOCAL)
ffffffff8123bd79-ffffffff8123bd8c: wb_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81248fc0)
Location: mm/backing-dev.c:347
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff81248fc0-ffffffff81249081: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81277110)
Location: mm/backing-dev.c:346
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff81277110-ffffffff812771d1: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81281a00)
Location: mm/backing-dev.c:335
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff81281a00-ffffffff81281ac1: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812868b0)
Location: mm/backing-dev.c:334
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff812868b0-ffffffff81286971: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c5c30)
Location: mm/backing-dev.c:344
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff812c5c30-ffffffff812c5d01: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813229d0)
Location: mm/backing-dev.c:334
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff813229d0-ffffffff81322ab4: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81397170)
Location: mm/backing-dev.c:461
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff81397170-ffffffff81397254: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813ca100)
Location: mm/backing-dev.c:466
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff813ca100-ffffffff813ca1e4: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f4a90)
Location: mm/backing-dev.c:464
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff813f4a90-ffffffff813f4b74: wb_shutdown (STB_LOCAL)
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
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102dddf0)
Location: mm/backing-dev.c:347
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffff8000102dddf0-ffff8000102ddfd4: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c0503468)
Location: mm/backing-dev.c:347
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
c0503468-c050353c: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039d8a0)
Location: mm/backing-dev.c:347
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
c00000000039d8a0-c00000000039da10: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f621c)
Location: mm/backing-dev.c:347
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffe0001f621c-ffffffe0001f631a: wb_shutdown (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81241610)
Location: mm/backing-dev.c:347
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff81241610-ffffffff812416d1: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81234610)
Location: mm/backing-dev.c:347
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff81234610-ffffffff812346c7: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123f3b0)
Location: mm/backing-dev.c:347
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff8123f3b0-ffffffff8123f471: wb_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wb_shutdown(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124e740)
Location: mm/backing-dev.c:347
Inline: True
Direct callers:
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:bdi_unregister
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff8124e740-ffffffff8124e7eb: wb_shutdown (STB_LOCAL)
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
