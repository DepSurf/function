# Function: <code>destroy_worker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81097150)
Location: kernel/workqueue.c:1758
Inline: False
Direct callers:
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:put_unbound_pool
```
**Symbols:**

```
ffffffff81097150-ffffffff810971d9: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109a8a0)
Location: kernel/workqueue.c:1814
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff8109a8a0-ffffffff8109a92c: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109f2d0)
Location: kernel/workqueue.c:1816
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff8109f2d0-ffffffff8109f35c: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109ca60)
Location: kernel/workqueue.c:1815
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff8109ca60-ffffffff8109cabc: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3330)
Location: kernel/workqueue.c:1816
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810a3330-ffffffff810a338f: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a9e50)
Location: kernel/workqueue.c:1850
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810a9e50-ffffffff810a9eaf: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b2ed0)
Location: kernel/workqueue.c:1870
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810b2ed0-ffffffff810b2f2f: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:1966
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810b8a90-ffffffff810b8af1: destroy_worker (STB_LOCAL)
ffffffff810bef0a-ffffffff810bef43: destroy_worker.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bef60)
Location: kernel/workqueue.c:1969
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810bef60-ffffffff810befbc: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6230)
Location: kernel/workqueue.c:1966
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810c6230-ffffffff810c628c: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c12b0)
Location: kernel/workqueue.c:1972
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810c12b0-ffffffff810c130c: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2c90)
Location: kernel/workqueue.c:1973
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810c2c90-ffffffff810c2cec: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d57d0)
Location: kernel/workqueue.c:2002
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810d57d0-ffffffff810d582c: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ee7f0)
Location: kernel/workqueue.c:1985
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810ee7f0-ffffffff810ee874: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8110fd90)
Location: kernel/workqueue.c:1985
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff8110fd90-ffffffff8110fe14: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011ba80)
Location: kernel/workqueue.c:1969
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffff80001011ba80-ffff80001011bb20: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c03700a0)
Location: kernel/workqueue.c:1969
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
c03700a0-c0370170: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0000000001639d0)
Location: kernel/workqueue.c:1969
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
c0000000001639d0-c000000000163aa4: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d5f2e)
Location: kernel/workqueue.c:1969
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffe0000d5f2e-ffffffe0000d5fa2: destroy_worker (STB_LOCAL)
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
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b92d0)
Location: kernel/workqueue.c:1969
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810b92d0-ffffffff810b932c: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a7c10)
Location: kernel/workqueue.c:1969
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810a7c10-ffffffff810a7c6c: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8830)
Location: kernel/workqueue.c:1969
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810b8830-ffffffff810b888c: destroy_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void destroy_worker(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c0c20)
Location: kernel/workqueue.c:1969
Inline: False
Direct callers:
  - kernel/workqueue.c:put_unbound_pool
  - kernel/workqueue.c:idle_worker_timeout
```
**Symbols:**

```
ffffffff810c0c20-ffffffff810c0c7c: destroy_worker (STB_LOCAL)
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
