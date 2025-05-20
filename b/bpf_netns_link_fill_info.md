# Function: <code>bpf_netns_link_fill_info</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_netns_link_fill_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8122a785)
Location: kernel/bpf/net_namespace.c:108
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
```
**Symbols:**

```
ffffffff8122a560-ffffffff8122a5bc: bpf_netns_link_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bpf_netns_link_fill_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81232537)
Location: kernel/bpf/net_namespace.c:203
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
```
**Symbols:**

```
ffffffff81232100-ffffffff8123215f: bpf_netns_link_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bpf_netns_link_fill_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff812366d7)
Location: kernel/bpf/net_namespace.c:203
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
```
**Symbols:**

```
ffffffff81236280-ffffffff812362df: bpf_netns_link_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bpf_netns_link_fill_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81270cb7)
Location: kernel/bpf/net_namespace.c:203
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
```
**Symbols:**

```
ffffffff812704d0-ffffffff8127052f: bpf_netns_link_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bpf_netns_link_fill_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff812bfd97)
Location: kernel/bpf/net_namespace.c:204
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
```
**Symbols:**

```
ffffffff812bf5d0-ffffffff812bf639: bpf_netns_link_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bpf_netns_link_fill_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff81323577)
Location: kernel/bpf/net_namespace.c:204
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
```
**Symbols:**

```
ffffffff81322d10-ffffffff81322d79: bpf_netns_link_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bpf_netns_link_fill_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff813537a7)
Location: kernel/bpf/net_namespace.c:204
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
```
**Symbols:**

```
ffffffff81352f80-ffffffff81352fe9: bpf_netns_link_fill_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_netns_link_fill_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/net_namespace.c (ffffffff8137ac97)
Location: kernel/bpf/net_namespace.c:204
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:bpf_netns_link_show_fdinfo
```
**Symbols:**

```
ffffffff8137a470-ffffffff8137a4d9: bpf_netns_link_fill_info (STB_LOCAL)
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
