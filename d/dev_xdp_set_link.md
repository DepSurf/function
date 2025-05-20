# Function: <code>dev_xdp_set_link</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0071a)
Location: net/core/dev.c:9085
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
  - net/core/dev.c:dev_xdp_uninstall
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
In net/core/dev.c (ffffffff819ec60b)
Location: net/core/dev.c:9344
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
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
In net/core/dev.c (ffffffff81a9d502)
Location: net/core/dev.c:9335
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
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
In net/core/dev.c (ffffffff81c16a2a)
Location: net/core/dev.c:9073
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
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
In net/core/dev.c (ffffffff81dd0d2c)
Location: net/core/dev.c:9060
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
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
In net/core/dev.c (ffffffff81e4192c)
Location: net/core/dev.c:9068
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
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
In net/core/dev.c (ffffffff81f0033f)
Location: net/core/dev.c:9186
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_many_notify
  - net/core/dev.c:bpf_xdp_link_release
  - net/core/dev.c:dev_xdp_attach
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
