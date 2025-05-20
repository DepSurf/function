# Function: <code>bpf_link_free</code>

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
void bpf_link_free(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200a70)
Location: kernel/bpf/syscall.c:2306
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_put_deferred
```
**Symbols:**

```
ffffffff81200a70-ffffffff81200ae5: bpf_link_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_link_free(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fff30)
Location: kernel/bpf/syscall.c:2322
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_put_deferred
```
**Symbols:**

```
ffffffff811fff30-ffffffff811fffa5: bpf_link_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_link_free(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812008e0)
Location: kernel/bpf/syscall.c:2330
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_put_deferred
```
**Symbols:**

```
ffffffff812008e0-ffffffff81200955: bpf_link_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_link_free(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81232650)
Location: kernel/bpf/syscall.c:2440
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_put_deferred
```
**Symbols:**

```
ffffffff81232650-ffffffff812326c5: bpf_link_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_link_free(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81275970)
Location: kernel/bpf/syscall.c:2688
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_put_deferred
```
**Symbols:**

```
ffffffff81275970-ffffffff812759ed: bpf_link_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_link_free(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c68e0)
Location: kernel/bpf/syscall.c:2722
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_put_deferred
```
**Symbols:**

```
ffffffff812c68e0-ffffffff812c695d: bpf_link_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_link_free(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812edbe0)
Location: kernel/bpf/syscall.c:2835
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_put_deferred
```
**Symbols:**

```
ffffffff812edbe0-ffffffff812edc5d: bpf_link_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_link_free(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130c790)
Location: kernel/bpf/syscall.c:2899
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:bpf_link_put_deferred
```
**Symbols:**

```
ffffffff8130c790-ffffffff8130c80d: bpf_link_free (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
