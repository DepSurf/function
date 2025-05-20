# Function: <code>bpf_event_notify</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b3890)
Location: kernel/trace/bpf_trace.c:1263
Inline: True
```
**Symbols:**

```
ffffffff811b3890-ffffffff811b3992: bpf_event_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2640)
Location: kernel/trace/bpf_trace.c:1449
Inline: True
```
**Symbols:**

```
ffffffff811c2640-ffffffff811c273f: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cddb0)
Location: kernel/trace/bpf_trace.c:1473
Inline: True
```
**Symbols:**

```
ffffffff811cddb0-ffffffff811cdeaf: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9a20)
Location: kernel/trace/bpf_trace.c:1967
Inline: True
```
**Symbols:**

```
ffffffff811e9a20-ffffffff811e9b1f: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e6e60)
Location: kernel/trace/bpf_trace.c:2223
Inline: True
```
**Symbols:**

```
ffffffff811e6e60-ffffffff811e6fac: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8200)
Location: kernel/trace/bpf_trace.c:1920
Inline: True
```
**Symbols:**

```
ffffffff811e8200-ffffffff811e834c: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81218e80)
Location: kernel/trace/bpf_trace.c:2004
Inline: True
```
**Symbols:**

```
ffffffff81218e80-ffffffff81218fcc: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812580e0)
Location: kernel/trace/bpf_trace.c:2185
Inline: False
```
**Symbols:**

```
ffffffff812580e0-ffffffff81258216: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a7d30)
Location: kernel/trace/bpf_trace.c:2408
Inline: False
```
**Symbols:**

```
ffffffff812a7d30-ffffffff812a7e66: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c9fc0)
Location: kernel/trace/bpf_trace.c:2417
Inline: False
```
**Symbols:**

```
ffffffff812c9fc0-ffffffff812ca0f6: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e7110)
Location: kernel/trace/bpf_trace.c:2527
Inline: False
```
**Symbols:**

```
ffffffff812e7110-ffffffff812e7275: bpf_event_notify (STB_LOCAL)
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
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024cd68)
Location: kernel/trace/bpf_trace.c:1473
Inline: True
```
**Symbols:**

```
ffff80001024cd68-ffff80001024ce7c: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0480b58)
Location: kernel/trace/bpf_trace.c:1473
Inline: True
```
**Symbols:**

```
c0480b58-c0480c5c: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002ea140)
Location: kernel/trace/bpf_trace.c:1473
Inline: True
```
**Symbols:**

```
c0000000002ea140-c0000000002ea2d4: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c63d0)
Location: kernel/trace/bpf_trace.c:1473
Inline: True
```
**Symbols:**

```
ffffffff811c63d0-ffffffff811c64cf: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b91b0)
Location: kernel/trace/bpf_trace.c:1473
Inline: True
```
**Symbols:**

```
ffffffff811b91b0-ffffffff811b92af: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c41a0)
Location: kernel/trace/bpf_trace.c:1473
Inline: True
```
**Symbols:**

```
ffffffff811c41a0-ffffffff811c429f: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bpf_event_notify(struct notifier_block *nb, long unsigned int op, void *module);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d1ac0)
Location: kernel/trace/bpf_trace.c:1473
Inline: True
```
**Symbols:**

```
ffffffff811d1ac0-ffffffff811d1bbf: bpf_event_notify (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
