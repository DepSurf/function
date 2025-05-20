# Function: <code>get_unbound_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b6f5)
Location: kernel/workqueue.c:3207
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109ed05)
Location: kernel/workqueue.c:3308
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3bdf)
Location: kernel/workqueue.c:3334
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
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
In kernel/workqueue.c (ffffffff810a0d5f)
Location: kernel/workqueue.c:3332
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a759c)
Location: kernel/workqueue.c:3343
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ae105)
Location: kernel/workqueue.c:3416
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b7235)
Location: kernel/workqueue.c:3439
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bc5c5)
Location: kernel/workqueue.c:3578
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3315)
Location: kernel/workqueue.c:3587
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct worker_pool *get_unbound_pool(const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810cada0)
Location: kernel/workqueue.c:3596
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810cada0-ffffffff810cb00b: get_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct worker_pool *get_unbound_pool(const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5ed0)
Location: kernel/workqueue.c:3602
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810c5ed0-ffffffff810c613b: get_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct worker_pool *get_unbound_pool(const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7810)
Location: kernel/workqueue.c:3603
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810c7810-ffffffff810c7a64: get_unbound_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct worker_pool *get_unbound_pool(const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3642
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810da570-ffffffff810da7dc: get_unbound_pool (STB_LOCAL)
ffffffff81ca525f-ffffffff81ca5287: get_unbound_pool.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct worker_pool *get_unbound_pool(const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3625
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810f3cb0-ffffffff810f3f48: get_unbound_pool (STB_LOCAL)
ffffffff81e54b95-ffffffff81e54bbe: get_unbound_pool.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct worker_pool *get_unbound_pool(const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3632
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff81115f00-ffffffff8111618a: get_unbound_pool (STB_LOCAL)
ffffffff8205668d-ffffffff820566b6: get_unbound_pool.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct worker_pool *get_unbound_pool(const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3960
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff81122ca0-ffffffff81122f2a: get_unbound_pool (STB_LOCAL)
ffffffff820d4c23-ffffffff820d4c4c: get_unbound_pool.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct worker_pool *get_unbound_pool(const struct workqueue_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4047
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff8112cc80-ffffffff8112cf4e: get_unbound_pool (STB_LOCAL)
ffffffff821afb4c-ffffffff821afb7b: get_unbound_pool.cold (STB_LOCAL)
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
In kernel/workqueue.c (ffff8000101210a0)
Location: kernel/workqueue.c:3587
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
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
In kernel/workqueue.c (c0374fe0)
Location: kernel/workqueue.c:3587
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
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
In kernel/workqueue.c (c00000000016a61c)
Location: kernel/workqueue.c:3587
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
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
In kernel/workqueue.c (ffffffe0000d9fec)
Location: kernel/workqueue.c:3587
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd685)
Location: kernel/workqueue.c:3587
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810abeb5)
Location: kernel/workqueue.c:3587
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bcbe5)
Location: kernel/workqueue.c:3587
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4f65)
Location: kernel/workqueue.c:3587
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
