# Function: <code>release_bdi</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e1416)
Location: mm/backing-dev.c:943
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f7410)
Location: mm/backing-dev.c:958
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffff811f7410-ffffffff811f74b5: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81218670)
Location: mm/backing-dev.c:956
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffff81218670-ffffffff81218712: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122b580)
Location: mm/backing-dev.c:959
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffff8122b580-ffffffff8122b622: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123b1c0)
Location: mm/backing-dev.c:946
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffff8123b1c0-ffffffff8123b263: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812496e0)
Location: mm/backing-dev.c:1027
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffff812496e0-ffffffff81249783: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81277910)
Location: mm/backing-dev.c:1017
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffff81277910-ffffffff812779b5: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81281fc0)
Location: mm/backing-dev.c:887
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffff81281fc0-ffffffff81282011: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812870d0)
Location: mm/backing-dev.c:886
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffff812870d0-ffffffff81287121: release_bdi (STB_LOCAL)
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
In mm/backing-dev.c (ffffffff812c6727)
Location: mm/backing-dev.c:969
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81323600)
Location: mm/backing-dev.c:960
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff81323600-ffffffff8132369e: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81397e60)
Location: mm/backing-dev.c:1083
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff81397e60-ffffffff81397efe: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813cade0)
Location: mm/backing-dev.c:1096
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff813cade0-ffffffff813cae7e: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f5000)
Location: mm/backing-dev.c:1092
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
```
**Symbols:**

```
ffffffff813f5000-ffffffff813f504f: release_bdi (STB_LOCAL)
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
In mm/backing-dev.c (ffff8000102def1c)
Location: mm/backing-dev.c:1027
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_put
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
In mm/backing-dev.c (c0503dbc)
Location: mm/backing-dev.c:1027
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_put
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
In mm/backing-dev.c (c00000000039e874)
Location: mm/backing-dev.c:1027
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_put
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f6ce0)
Location: mm/backing-dev.c:1027
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffe0001f6ce0-ffffffe0001f6dbc: release_bdi (STB_LOCAL)
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
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81241d30)
Location: mm/backing-dev.c:1027
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffff81241d30-ffffffff81241dd3: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81234d10)
Location: mm/backing-dev.c:1027
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffff81234d10-ffffffff81234dad: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123fad0)
Location: mm/backing-dev.c:1027
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffff8123fad0-ffffffff8123fb73: release_bdi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void release_bdi(struct kref *ref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124f240)
Location: mm/backing-dev.c:1027
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
**Symbols:**

```
ffffffff8124f240-ffffffff8124f2da: release_bdi (STB_LOCAL)
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
