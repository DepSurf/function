# Function: <code>napi_kthread_create</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int napi_kthread_create(struct napi_struct *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1558
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_set_threaded
```
**Symbols:**

```
ffffffff819e5dd0-ffffffff819e5e32: napi_kthread_create (STB_LOCAL)
ffffffff81c22e97-ffffffff81c22eb7: napi_kthread_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int napi_kthread_create(struct napi_struct *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1433
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_add
  - net/core/dev.c:dev_set_threaded
```
**Symbols:**

```
ffffffff81a962f0-ffffffff81a96352: napi_kthread_create (STB_LOCAL)
ffffffff81d3578d-ffffffff81d357ad: napi_kthread_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int napi_kthread_create(struct napi_struct *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1380
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_set_threaded
```
**Symbols:**

```
ffffffff81c0cfc0-ffffffff81c0d034: napi_kthread_create (STB_LOCAL)
ffffffff81f01d79-ffffffff81f01d99: napi_kthread_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int napi_kthread_create(struct napi_struct *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbcbb0)
Location: net/core/dev.c:1365
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_set_threaded
```
**Symbols:**

```
ffffffff81dbcbb0-ffffffff81dbcc3d: napi_kthread_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int napi_kthread_create(struct napi_struct *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2d3c0)
Location: net/core/dev.c:1390
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_set_threaded
```
**Symbols:**

```
ffffffff81e2d3c0-ffffffff81e2d44d: napi_kthread_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int napi_kthread_create(struct napi_struct *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eeb6a0)
Location: net/core/dev.c:1394
Inline: False
Direct callers:
  - net/core/dev.c:netif_napi_add_weight
  - net/core/dev.c:dev_set_threaded
```
**Symbols:**

```
ffffffff81eeb6a0-ffffffff81eeb734: napi_kthread_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
