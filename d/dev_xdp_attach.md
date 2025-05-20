# Function: <code>dev_xdp_attach</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_xdp_attach(struct net_device *dev, struct netlink_ext_ack *extack, struct bpf_xdp_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a00550)
Location: net/core/dev.c:9164
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81a00550-ffffffff81a00998: dev_xdp_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_xdp_attach(struct net_device *dev, struct netlink_ext_ack *extack, struct bpf_xdp_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e69d0)
Location: net/core/dev.c:9423
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff819e69d0-ffffffff819e6ea3: dev_xdp_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_xdp_attach(struct net_device *dev, struct netlink_ext_ack *extack, struct bpf_xdp_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9414
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81a9b260-ffffffff81a9b7d8: dev_xdp_attach (STB_LOCAL)
ffffffff81d36060-ffffffff81d360bc: dev_xdp_attach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_xdp_attach(struct net_device *dev, struct netlink_ext_ack *extack, struct bpf_xdp_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9152
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81c14910-ffffffff81c151e6: dev_xdp_attach (STB_LOCAL)
ffffffff81f028df-ffffffff81f0292b: dev_xdp_attach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dev_xdp_attach(struct net_device *dev, struct netlink_ext_ack *extack, struct bpf_xdp_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9139
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81dc5a50-ffffffff81dc6326: dev_xdp_attach (STB_LOCAL)
ffffffff820ab49f-ffffffff820ab4eb: dev_xdp_attach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dev_xdp_attach(struct net_device *dev, struct netlink_ext_ack *extack, struct bpf_xdp_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9147
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81e34ea0-ffffffff81e35805: dev_xdp_attach (STB_LOCAL)
ffffffff8212cad4-ffffffff8212cb57: dev_xdp_attach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dev_xdp_attach(struct net_device *dev, struct netlink_ext_ack *extack, struct bpf_xdp_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9265
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:dev_change_xdp_fd
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81ef2f40-ffffffff81ef389f: dev_xdp_attach (STB_LOCAL)
ffffffff8220e7fe-ffffffff8220e881: dev_xdp_attach.cold (STB_LOCAL)
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
