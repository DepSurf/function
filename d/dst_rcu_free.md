# Function: <code>dst_rcu_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
void dst_rcu_free(struct callback_head *head);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81754650)
Location: include/net/dst.h:426
Inline: False
```
```
In net/ipv6/ip6_fib.c (ffffffff817da8d0)
Location: include/net/dst.h:426
Inline: False
```
**Symbols:**

```
ffffffff81754650-ffffffff8175467a: dst_rcu_free (STB_LOCAL)
ffffffff817da8d0-ffffffff817da8fa: dst_rcu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
void dst_rcu_free(struct callback_head *head);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c07e0)
Location: include/net/dst.h:435
Inline: False
```
```
In net/ipv6/ip6_fib.c (ffffffff81848fc0)
Location: include/net/dst.h:435
Inline: False
```
**Symbols:**

```
ffffffff817c07e0-ffffffff817c080a: dst_rcu_free (STB_LOCAL)
ffffffff81848fc0-ffffffff81848fea: dst_rcu_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
void dst_rcu_free(struct callback_head *head);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817efa90)
Location: include/net/dst.h:435
Inline: False
```
```
In net/ipv6/ip6_fib.c (ffffffff8187ae10)
Location: include/net/dst.h:435
Inline: False
```
**Symbols:**

```
ffffffff817efa90-ffffffff817efaba: dst_rcu_free (STB_LOCAL)
ffffffff8187ae10-ffffffff8187ae3a: dst_rcu_free (STB_LOCAL)
```
</details>
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
</ul>
