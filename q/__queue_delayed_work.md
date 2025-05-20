# Function: <code>__queue_delayed_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81098470)
Location: kernel/workqueue.c:1446
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff81098470-ffffffff810985ec: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109ba70)
Location: kernel/workqueue.c:1502
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff8109ba70-ffffffff8109bbf7: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a09a0)
Location: kernel/workqueue.c:1504
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810a09a0-ffffffff810a0b27: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109db40)
Location: kernel/workqueue.c:1504
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff8109db40-ffffffff8109dbd8: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a4270)
Location: kernel/workqueue.c:1506
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810a4270-ffffffff810a42fc: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ac6b0)
Location: kernel/workqueue.c:1504
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810ac6b0-ffffffff810ac732: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b55c0)
Location: kernel/workqueue.c:1524
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810b55c0-ffffffff810b5642: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bb4b0)
Location: kernel/workqueue.c:1620
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810bb4b0-ffffffff810bb53c: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c1720)
Location: kernel/workqueue.c:1623
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810c1720-ffffffff810c17ac: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ca420)
Location: kernel/workqueue.c:1620
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810ca420-ffffffff810ca4b0: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5550)
Location: kernel/workqueue.c:1626
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810c5550-ffffffff810c55e0: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6e50)
Location: kernel/workqueue.c:1627
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810c6e50-ffffffff810c6ee0: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d9b80)
Location: kernel/workqueue.c:1657
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810d9b80-ffffffff810d9c10: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f1be0)
Location: kernel/workqueue.c:1647
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810f1be0-ffffffff810f1cc3: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81115320)
Location: kernel/workqueue.c:1647
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff81115320-ffffffff81115403: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811212f0)
Location: kernel/workqueue.c:1849
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff811212f0-ffffffff811213d3: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112ba40)
Location: kernel/workqueue.c:1935
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff8112ba40-ffffffff8112bb23: __queue_delayed_work (STB_LOCAL)
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
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011fb88)
Location: kernel/workqueue.c:1623
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffff80001011fb88-ffff80001011fc84: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0372a40)
Location: kernel/workqueue.c:1623
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
c0372a40-c0372bcc: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0000000001659e0)
Location: kernel/workqueue.c:1623
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
c0000000001659e0-c000000000165af0: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d8978)
Location: kernel/workqueue.c:1623
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffe0000d8978-ffffffe0000d8a3e: __queue_delayed_work (STB_LOCAL)
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
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bba90)
Location: kernel/workqueue.c:1623
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810bba90-ffffffff810bbb1c: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aa510)
Location: kernel/workqueue.c:1623
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810aa510-ffffffff810aa59c: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810baff0)
Location: kernel/workqueue.c:1623
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810baff0-ffffffff810bb07c: __queue_delayed_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __queue_delayed_work(int cpu, struct workqueue_struct *wq, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c24e0)
Location: kernel/workqueue.c:1623
Inline: False
Direct callers:
  - kernel/workqueue.c:mod_delayed_work_on
  - kernel/workqueue.c:queue_delayed_work_on
```
**Symbols:**

```
ffffffff810c24e0-ffffffff810c256c: __queue_delayed_work (STB_LOCAL)
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
