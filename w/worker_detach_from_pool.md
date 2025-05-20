# Function: <code>worker_detach_from_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81097200)
Location: kernel/workqueue.c:1667
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:rescuer_thread
```
**Symbols:**

```
ffffffff81097200-ffffffff810972a1: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109a950)
Location: kernel/workqueue.c:1723
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff8109a950-ffffffff8109a9f4: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109f440)
Location: kernel/workqueue.c:1725
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff8109f440-ffffffff8109f4e4: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109cc20)
Location: kernel/workqueue.c:1724
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff8109cc20-ffffffff8109ccc0: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3470)
Location: kernel/workqueue.c:1725
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810a3470-ffffffff810a3510: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a9fc0)
Location: kernel/workqueue.c:1757
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810a9fc0-ffffffff810aa068: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b3090)
Location: kernel/workqueue.c:1777
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810b3090-ffffffff810b3138: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8c60)
Location: kernel/workqueue.c:1873
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810b8c60-ffffffff810b8d06: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bf1a0)
Location: kernel/workqueue.c:1876
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810bf1a0-ffffffff810bf246: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6460)
Location: kernel/workqueue.c:1873
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810c6460-ffffffff810c6506: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c14e0)
Location: kernel/workqueue.c:1878
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810c14e0-ffffffff810c1594: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2ec0)
Location: kernel/workqueue.c:1879
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810c2ec0-ffffffff810c2f74: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d5a00)
Location: kernel/workqueue.c:1909
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810d5a00-ffffffff810d5ab4: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810eede0)
Location: kernel/workqueue.c:1892
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810eede0-ffffffff810eeeac: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81110480)
Location: kernel/workqueue.c:1892
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff81110480-ffffffff8111054c: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111c660)
Location: kernel/workqueue.c:2094
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff8111c660-ffffffff8111c741: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81125ff0)
Location: kernel/workqueue.c:2134
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff81125ff0-ffffffff811260d1: worker_detach_from_pool (STB_LOCAL)
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
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011be90)
Location: kernel/workqueue.c:1876
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffff80001011be90-ffff80001011bf48: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c03706ec)
Location: kernel/workqueue.c:1876
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
c03706ec-c0370798: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000164070)
Location: kernel/workqueue.c:1876
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
c000000000164070-c000000000164184: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d621e)
Location: kernel/workqueue.c:1876
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffe0000d621e-ffffffe0000d62c0: worker_detach_from_pool (STB_LOCAL)
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
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9510)
Location: kernel/workqueue.c:1876
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810b9510-ffffffff810b95b6: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a7e50)
Location: kernel/workqueue.c:1876
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810a7e50-ffffffff810a7ef6: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8a70)
Location: kernel/workqueue.c:1876
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810b8a70-ffffffff810b8b16: worker_detach_from_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void worker_detach_from_pool(struct worker *worker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c11f0)
Location: kernel/workqueue.c:1876
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810c11f0-ffffffff810c1296: worker_detach_from_pool (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct worker_pool *pool</code>
</li>
</ul>
</details>
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
