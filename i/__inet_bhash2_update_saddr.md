# Function: <code>__inet_bhash2_update_saddr</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __inet_bhash2_update_saddr(struct sock *sk, void *saddr, int family, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (0)
Location: net/ipv4/inet_hashtables.c:888
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_bhash2_update_saddr
```
**Symbols:**

```
ffffffff81ea49f0-ffffffff81ea4f7d: __inet_bhash2_update_saddr (STB_LOCAL)
ffffffff820ae590-ffffffff820ae5d4: __inet_bhash2_update_saddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __inet_bhash2_update_saddr(struct sock *sk, void *saddr, int family, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f03280)
Location: net/ipv4/inet_hashtables.c:878
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_bhash2_update_saddr
```
**Symbols:**

```
ffffffff81f03280-ffffffff81f03750: __inet_bhash2_update_saddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __inet_bhash2_update_saddr(struct sock *sk, void *saddr, int family, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc74d0)
Location: net/ipv4/inet_hashtables.c:890
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:inet_bhash2_update_saddr
```
**Symbols:**

```
ffffffff81fc74d0-ffffffff81fc79dd: __inet_bhash2_update_saddr (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
