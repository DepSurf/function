# Function: <code>ensure_safe_net_sysctl</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ensure_safe_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81b9b8d0)
Location: net/sysctl_net.c:124
Inline: False
Direct callers:
  - net/sysctl_net.c:register_net_sysctl
```
**Symbols:**

```
ffffffff81b9b8d0-ffffffff81b9b9b5: ensure_safe_net_sysctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ensure_safe_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81c68820)
Location: net/sysctl_net.c:124
Inline: False
Direct callers:
  - net/sysctl_net.c:register_net_sysctl
```
**Symbols:**

```
ffffffff81c68820-ffffffff81c688ff: ensure_safe_net_sysctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ensure_safe_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81e0b990)
Location: net/sysctl_net.c:124
Inline: False
Direct callers:
  - net/sysctl_net.c:register_net_sysctl
```
**Symbols:**

```
ffffffff81e0b990-ffffffff81e0baa5: ensure_safe_net_sysctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ensure_safe_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81fe1630)
Location: net/sysctl_net.c:124
Inline: False
Direct callers:
  - net/sysctl_net.c:register_net_sysctl
```
**Symbols:**

```
ffffffff81fe1630-ffffffff81fe1745: ensure_safe_net_sysctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ensure_safe_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff8205d8b0)
Location: net/sysctl_net.c:124
Inline: False
Direct callers:
  - net/sysctl_net.c:register_net_sysctl
```
**Symbols:**

```
ffffffff8205d8b0-ffffffff8205d9c5: ensure_safe_net_sysctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ensure_safe_net_sysctl(struct net *net, const char *path, struct ctl_table *table, size_t table_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff821304e0)
Location: net/sysctl_net.c:124
Inline: False
Direct callers:
  - net/sysctl_net.c:register_net_sysctl_sz
```
**Symbols:**

```
ffffffff821304e0-ffffffff82130621: ensure_safe_net_sysctl (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t table_size</code>
</li>
</ul>
</details>
</li>
</ul>
