# Function: <code>bpf_dispatcher_prepare</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_dispatcher_prepare(struct bpf_dispatcher *d, void *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/dispatcher.c (ffffffff81226180)
Location: kernel/bpf/dispatcher.c:93
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff81226180-ffffffff8122620f: bpf_dispatcher_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_dispatcher_prepare(struct bpf_dispatcher *d, void *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/dispatcher.c (ffffffff8122cd70)
Location: kernel/bpf/dispatcher.c:93
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff8122cd70-ffffffff8122cdff: bpf_dispatcher_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_dispatcher_prepare(struct bpf_dispatcher *d, void *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/dispatcher.c (ffffffff81231bd0)
Location: kernel/bpf/dispatcher.c:93
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff81231bd0-ffffffff81231c5f: bpf_dispatcher_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_dispatcher_prepare(struct bpf_dispatcher *d, void *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/dispatcher.c (ffffffff8126ab90)
Location: kernel/bpf/dispatcher.c:93
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff8126ab90-ffffffff8126ac92: bpf_dispatcher_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_dispatcher_prepare(struct bpf_dispatcher *d, void *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/dispatcher.c (ffffffff812b9770)
Location: kernel/bpf/dispatcher.c:93
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff812b9770-ffffffff812b9885: bpf_dispatcher_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_dispatcher_prepare(struct bpf_dispatcher *d, void *image, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/dispatcher.c (ffffffff8131c900)
Location: kernel/bpf/dispatcher.c:94
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff8131c900-ffffffff8131ca3e: bpf_dispatcher_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_dispatcher_prepare(struct bpf_dispatcher *d, void *image, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/dispatcher.c (ffffffff8134c600)
Location: kernel/bpf/dispatcher.c:94
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff8134c600-ffffffff8134c73e: bpf_dispatcher_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_dispatcher_prepare(struct bpf_dispatcher *d, void *image, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/dispatcher.c (ffffffff81373b30)
Location: kernel/bpf/dispatcher.c:94
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff81373b30-ffffffff81373c6e: bpf_dispatcher_prepare (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *buf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
