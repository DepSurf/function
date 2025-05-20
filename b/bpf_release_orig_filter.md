# Function: <code>bpf_release_orig_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81731c89)
Location: net/core/filter.c:859
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_prog_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179d099)
Location: net/core/filter.c:883
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_prog_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cab49)
Location: net/core/filter.c:885
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_prog_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9cc9)
Location: net/core/filter.c:903
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81865339)
Location: net/core/filter.c:922
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2ed9)
Location: net/core/filter.c:1131
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d7db9)
Location: net/core/filter.c:1133
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192585a)
Location: net/core/filter.c:1133
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81957c8a)
Location: net/core/filter.c:1133
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a32642)
Location: net/core/filter.c:1122
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:sk_filter_release_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a34982)
Location: net/core/filter.c:1152
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:sk_filter_release_rcu
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
In net/core/filter.c (ffffffff81a1b9f2)
Location: net/core/filter.c:1152
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
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
In net/core/filter.c (ffffffff81acf0d2)
Location: net/core/filter.c:1153
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
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
In net/core/filter.c (ffffffff81c4c7d1)
Location: net/core/filter.c:1154
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
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
In net/core/filter.c (ffffffff81e015c1)
Location: net/core/filter.c:1156
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
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
In net/core/filter.c (ffffffff81e73081)
Location: net/core/filter.c:1156
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
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
In net/core/filter.c (ffffffff81f32801)
Location: net/core/filter.c:1161
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_prog_free
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_release_rcu
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf92d0)
Location: net/core/filter.c:1133
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d12ef8)
Location: net/core/filter.c:1133
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce0688)
Location: net/core/filter.c:1133
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077b2ba)
Location: net/core/filter.c:1133
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f7c5a)
Location: net/core/filter.c:1133
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b1a8a)
Location: net/core/filter.c:1133
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81948c8a)
Location: net/core/filter.c:1133
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196a59a)
Location: net/core/filter.c:1133
Inline: True
```
</details>
</li>
</ul>

## Differences
