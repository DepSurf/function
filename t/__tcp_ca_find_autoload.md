# Function: <code>__tcp_ca_find_autoload</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const struct tcp_congestion_ops *__tcp_ca_find_autoload(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff81780360)
Location: net/ipv4/tcp_cong.c:36
Inline: True
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
```
**Symbols:**

```
ffffffff81780360-ffffffff81780400: __tcp_ca_find_autoload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const struct tcp_congestion_ops *__tcp_ca_find_autoload(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff817ed840)
Location: net/ipv4/tcp_cong.c:36
Inline: True
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
```
**Symbols:**

```
ffffffff817ed840-ffffffff817ed8e0: __tcp_ca_find_autoload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const struct tcp_congestion_ops *__tcp_ca_find_autoload(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8181e170)
Location: net/ipv4/tcp_cong.c:36
Inline: True
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
```
**Symbols:**

```
ffffffff8181e170-ffffffff8181e216: __tcp_ca_find_autoload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const struct tcp_congestion_ops *__tcp_ca_find_autoload(const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cong.c (ffffffff8183e8d0)
Location: net/ipv4/tcp_cong.c:36
Inline: True
Direct callers:
  - net/ipv4/tcp_cong.c:tcp_set_congestion_control
  - net/ipv4/tcp_cong.c:tcp_ca_get_key_by_name
```
**Symbols:**

```
ffffffff8183e8d0-ffffffff8183e978: __tcp_ca_find_autoload (STB_LOCAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
