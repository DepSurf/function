# Function: <code>bpf_netns_link_release</code>

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
void bpf_netns_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8122a670)
Location: kernel/bpf/net_namespace.c:39
Inline: False
```
**Symbols:**

```
ffffffff8122a670-ffffffff8122a6ea: bpf_netns_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_netns_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81232270)
Location: kernel/bpf/net_namespace.c:101
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_detach
```
**Symbols:**

```
ffffffff81232270-ffffffff81232421: bpf_netns_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_netns_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff812363f0)
Location: kernel/bpf/net_namespace.c:101
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_detach
```
**Symbols:**

```
ffffffff812363f0-ffffffff812365a5: bpf_netns_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_netns_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81270720)
Location: kernel/bpf/net_namespace.c:101
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_detach
```
**Symbols:**

```
ffffffff81270720-ffffffff81270b8f: bpf_netns_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_netns_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff812bf840)
Location: kernel/bpf/net_namespace.c:102
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_detach
```
**Symbols:**

```
ffffffff812bf840-ffffffff812bfc90: bpf_netns_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_netns_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81322fb0)
Location: kernel/bpf/net_namespace.c:102
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_detach
```
**Symbols:**

```
ffffffff81322fb0-ffffffff81323404: bpf_netns_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_netns_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81353220)
Location: kernel/bpf/net_namespace.c:102
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_detach
```
**Symbols:**

```
ffffffff81353220-ffffffff8135366e: bpf_netns_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_netns_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8137a710)
Location: kernel/bpf/net_namespace.c:102
Inline: False
Direct callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_detach
```
**Symbols:**

```
ffffffff8137a710-ffffffff8137ab5e: bpf_netns_link_release (STB_LOCAL)
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
