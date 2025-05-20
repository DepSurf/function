# Function: <code>set_pf_worker</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_pf_worker(bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a9d20)
Location: kernel/workqueue.c:2216
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810a9d20-ffffffff810a9d74: set_pf_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_pf_worker(bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b2da0)
Location: kernel/workqueue.c:2239
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810b2da0-ffffffff810b2df4: set_pf_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_pf_worker(bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8970)
Location: kernel/workqueue.c:2335
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810b8970-ffffffff810b89bb: set_pf_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_pf_worker(bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bee40)
Location: kernel/workqueue.c:2338
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810bee40-ffffffff810bee8b: set_pf_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c9d47)
Location: kernel/workqueue.c:2335
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4e97)
Location: kernel/workqueue.c:2341
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c67d7)
Location: kernel/workqueue.c:2342
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810d9487)
Location: kernel/workqueue.c:2373
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f28b7)
Location: kernel/workqueue.c:2356
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81114b87)
Location: kernel/workqueue.c:2356
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81121a47)
Location: kernel/workqueue.c:2671
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112a83f)
Location: kernel/workqueue.c:2710
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
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
void set_pf_worker(bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011b900)
Location: kernel/workqueue.c:2338
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffff80001011b900-ffff80001011b96c: set_pf_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_pf_worker(bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c036fd90)
Location: kernel/workqueue.c:2338
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
c036fd90-c036fde8: set_pf_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_pf_worker(bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0000000001637d0)
Location: kernel/workqueue.c:2338
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
c0000000001637d0-c000000000163864: set_pf_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_pf_worker(bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d5dda)
Location: kernel/workqueue.c:2338
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffe0000d5dda-ffffffe0000d5e4a: set_pf_worker (STB_LOCAL)
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
void set_pf_worker(bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b91b0)
Location: kernel/workqueue.c:2338
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810b91b0-ffffffff810b91fb: set_pf_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_pf_worker(bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a7af0)
Location: kernel/workqueue.c:2338
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810a7af0-ffffffff810a7b3b: set_pf_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_pf_worker(bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8710)
Location: kernel/workqueue.c:2338
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810b8710-ffffffff810b875b: set_pf_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_pf_worker(bool val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c09e0)
Location: kernel/workqueue.c:2338
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810c09e0-ffffffff810c0a2b: set_pf_worker (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
