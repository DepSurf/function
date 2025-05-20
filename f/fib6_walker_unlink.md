# Function: <code>fib6_walker_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fib6_walker_unlink(struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817d9480)
Location: net/ipv6/ip6_fib.c:91
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_dump_end
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:inet6_dump_fib
```
**Symbols:**

```
ffffffff817d9480-ffffffff817d94d1: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff818473d0)
Location: net/ipv6/ip6_fib.c:89
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffff818473d0-ffffffff81847428: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81879210)
Location: net/ipv6/ip6_fib.c:89
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffff81879210-ffffffff81879268: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8189ebb0)
Location: net/ipv6/ip6_fib.c:89
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffff8189ebb0-ffffffff8189ec04: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81921180)
Location: net/ipv6/ip6_fib.c:85
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffff81921180-ffffffff819211d4: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81979580)
Location: net/ipv6/ip6_fib.c:85
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffff81979580-ffffffff819795d4: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819af130)
Location: net/ipv6/ip6_fib.c:87
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffff819af130-ffffffff819af184: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a1d320)
Location: net/ipv6/ip6_fib.c:83
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffff81a1d320-ffffffff81a1d36e: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a53f60)
Location: net/ipv6/ip6_fib.c:83
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffff81a53f60-ffffffff81a53fae: fib6_walker_unlink (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (ffffffff81b4c08e)
Location: net/ipv6/ip6_fib.c:83
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
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
In net/ipv6/ip6_fib.c (ffffffff81b5acce)
Location: net/ipv6/ip6_fib.c:83
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
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
In net/ipv6/ip6_fib.c (ffffffff81b48f4e)
Location: net/ipv6/ip6_fib.c:83
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
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
In net/ipv6/ip6_fib.c (ffffffff81c1025e)
Location: net/ipv6/ip6_fib.c:84
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
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
In net/ipv6/ip6_fib.c (ffffffff81dab466)
Location: net/ipv6/ip6_fib.c:85
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
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
In net/ipv6/ip6_fib.c (ffffffff81f7ada6)
Location: net/ipv6/ip6_fib.c:85
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
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
In net/ipv6/ip6_fib.c (ffffffff81fdafb6)
Location: net/ipv6/ip6_fib.c:85
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
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
In net/ipv6/ip6_fib.c (ffffffff820a8a06)
Location: net/ipv6/ip6_fib.c:85
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_clean_tree
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_dump_done
  - net/ipv6/ip6_fib.c:fib6_tables_dump
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d198b0)
Location: net/ipv6/ip6_fib.c:83
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffff800010d198b0-ffff800010d19974: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e1dc00)
Location: net/ipv6/ip6_fib.c:83
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_dump_table
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
c0e1dc00-c0e1dc4c: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e45d30)
Location: net/ipv6/ip6_fib.c:83
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
c000000000e45d30-c000000000e45dc4: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085cfaa)
Location: net/ipv6/ip6_fib.c:83
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffe00085cfaa-ffffffe00085d008: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f35f0)
Location: net/ipv6/ip6_fib.c:83
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffff819f35f0-ffffffff819f363e: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b03b0)
Location: net/ipv6/ip6_fib.c:83
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffff819b03b0-ffffffff819b03fe: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a5e070)
Location: net/ipv6/ip6_fib.c:83
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffff81a5e070-ffffffff81a5e0be: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fib6_walker_unlink(struct net *net, struct fib6_walker *w);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6a4a0)
Location: net/ipv6/ip6_fib.c:83
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_stop
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:ipv6_route_seq_next
  - net/ipv6/ip6_fib.c:fib6_walk
  - net/ipv6/ip6_fib.c:fib6_dump_end
```
**Symbols:**

```
ffffffff81a6a4a0-ffffffff81a6a4ee: fib6_walker_unlink (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>w</code> ➡️ <code>net, w</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
