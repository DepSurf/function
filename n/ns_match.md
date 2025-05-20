# Function: <code>ns_match</code>

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
bool ns_match(const struct ns_common *ns, dev_t dev, ino_t ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81356b30)
Location: fs/nsfs.c:263
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
**Symbols:**

```
ffffffff81356b30-ffffffff81356b58: ns_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ns_match(const struct ns_common *ns, dev_t dev, ino_t ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813634e0)
Location: fs/nsfs.c:263
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
**Symbols:**

```
ffffffff813634e0-ffffffff81363508: ns_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ns_match(const struct ns_common *ns, dev_t dev, ino_t ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81369f70)
Location: fs/nsfs.c:263
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
**Symbols:**

```
ffffffff81369f70-ffffffff81369f98: ns_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ns_match(const struct ns_common *ns, dev_t dev, ino_t ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff813b8c60)
Location: fs/nsfs.c:263
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
**Symbols:**

```
ffffffff813b8c60-ffffffff813b8c88: ns_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ns_match(const struct ns_common *ns, dev_t dev, ino_t ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff8143e5e0)
Location: fs/nsfs.c:263
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
**Symbols:**

```
ffffffff8143e5e0-ffffffff8143e620: ns_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ns_match(const struct ns_common *ns, dev_t dev, ino_t ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff814cd0a0)
Location: fs/nsfs.c:263
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
**Symbols:**

```
ffffffff814cd0a0-ffffffff814cd0e0: ns_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ns_match(const struct ns_common *ns, dev_t dev, ino_t ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81503280)
Location: fs/nsfs.c:246
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
**Symbols:**

```
ffffffff81503280-ffffffff815032c0: ns_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ns_match(const struct ns_common *ns, dev_t dev, ino_t ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/nsfs.c (ffffffff81537ea0)
Location: fs/nsfs.c:243
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_get_ns_current_pid_tgid
```
**Symbols:**

```
ffffffff81537ea0-ffffffff81537ee0: ns_match (STB_GLOBAL)
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
