# Function: <code>wq_update_unbound_numa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109bb40)
Location: kernel/workqueue.c:3687
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_cpu_up_callback
  - kernel/workqueue.c:workqueue_cpu_down_callback
```
**Symbols:**

```
ffffffff8109bb40-ffffffff8109bcfb: wq_update_unbound_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109f170)
Location: kernel/workqueue.c:3785
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
```
**Symbols:**

```
ffffffff8109f170-ffffffff8109f32b: wq_update_unbound_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a4080)
Location: kernel/workqueue.c:3813
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810a4080-ffffffff810a4244: wq_update_unbound_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a1150)
Location: kernel/workqueue.c:3822
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810a1150-ffffffff810a1354: wq_update_unbound_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a79c0)
Location: kernel/workqueue.c:3833
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810a79c0-ffffffff810a7bb3: wq_update_unbound_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3906
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810ae520-ffffffff810ae701: wq_update_unbound_numa (STB_LOCAL)
ffffffff810b029b-ffffffff810b02b3: wq_update_unbound_numa.cold.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:3929
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810b7680-ffffffff810b7861: wq_update_unbound_numa (STB_LOCAL)
ffffffff810b93db-ffffffff810b93f3: wq_update_unbound_numa.cold.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4069
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810bca20-ffffffff810bcc0f: wq_update_unbound_numa (STB_LOCAL)
ffffffff810bf044-ffffffff810bf05c: wq_update_unbound_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4082
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c3770-ffffffff810c396e: wq_update_unbound_numa (STB_LOCAL)
ffffffff810c552f-ffffffff810c5547: wq_update_unbound_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4091
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810cb080-ffffffff810cb270: wq_update_unbound_numa (STB_LOCAL)
ffffffff810cd0da-ffffffff810cd0f2: wq_update_unbound_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4104
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c61b0-ffffffff810c63a0: wq_update_unbound_numa (STB_LOCAL)
ffffffff81bdbf3b-ffffffff81bdbf53: wq_update_unbound_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4111
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c7ae0-ffffffff810c7d26: wq_update_unbound_numa (STB_LOCAL)
ffffffff81bce058-ffffffff81bce078: wq_update_unbound_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4150
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810da850-ffffffff810daabd: wq_update_unbound_numa (STB_LOCAL)
ffffffff81ca5287-ffffffff81ca52d1: wq_update_unbound_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4133
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810f3fc0-ffffffff810f41ff: wq_update_unbound_numa (STB_LOCAL)
ffffffff81e54bbe-ffffffff81e54c00: wq_update_unbound_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4142
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff81116220-ffffffff8111646b: wq_update_unbound_numa (STB_LOCAL)
ffffffff820566b6-ffffffff820566e0: wq_update_unbound_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4470
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff81122fc0-ffffffff8112320b: wq_update_unbound_numa (STB_LOCAL)
ffffffff820d4c4c-ffffffff820d4c76: wq_update_unbound_numa.cold (STB_LOCAL)
```
</details>
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
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010121488)
Location: kernel/workqueue.c:4082
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffff800010121488-ffff8000101216f4: wq_update_unbound_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0375234)
Location: kernel/workqueue.c:4082
Inline: False
```
**Symbols:**

```
c0375234-c037524c: wq_update_unbound_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016aab0)
Location: kernel/workqueue.c:4082
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
c00000000016aab0-c00000000016ad80: wq_update_unbound_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000da34e)
Location: kernel/workqueue.c:4082
Inline: False
```
**Symbols:**

```
ffffffe0000da34e-ffffffe0000da368: wq_update_unbound_numa (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4082
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810bdae0-ffffffff810bdcde: wq_update_unbound_numa (STB_LOCAL)
ffffffff810bf89f-ffffffff810bf8b7: wq_update_unbound_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4082
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810ac310-ffffffff810ac508: wq_update_unbound_numa (STB_LOCAL)
ffffffff810ae0bf-ffffffff810ae0d7: wq_update_unbound_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4082
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810bd040-ffffffff810bd23e: wq_update_unbound_numa (STB_LOCAL)
ffffffff810bedff-ffffffff810bee17: wq_update_unbound_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void wq_update_unbound_numa(struct workqueue_struct *wq, int cpu, bool online);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4082
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c53c0-ffffffff810c55b5: wq_update_unbound_numa (STB_LOCAL)
ffffffff810c716a-ffffffff810c7182: wq_update_unbound_numa.cold (STB_LOCAL)
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
