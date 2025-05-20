# Function: <code>cmp_nla_vrftable</code>

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
int cmp_nla_vrftable(struct seg6_local_lwt *a, struct seg6_local_lwt *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b8dd40)
Location: net/ipv6/seg6_local.c:1114
Inline: False
```
**Symbols:**

```
ffffffff81b8dd40-ffffffff81b8dd57: cmp_nla_vrftable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cmp_nla_vrftable(struct seg6_local_lwt *a, struct seg6_local_lwt *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7cc40)
Location: net/ipv6/seg6_local.c:1188
Inline: False
```
**Symbols:**

```
ffffffff81b7cc40-ffffffff81b7cc57: cmp_nla_vrftable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cmp_nla_vrftable(struct seg6_local_lwt *a, struct seg6_local_lwt *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81c47ed0)
Location: net/ipv6/seg6_local.c:1253
Inline: False
```
**Symbols:**

```
ffffffff81c47ed0-ffffffff81c47ee7: cmp_nla_vrftable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cmp_nla_vrftable(struct seg6_local_lwt *a, struct seg6_local_lwt *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81de73a0)
Location: net/ipv6/seg6_local.c:1253
Inline: False
```
**Symbols:**

```
ffffffff81de73a0-ffffffff81de73bf: cmp_nla_vrftable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cmp_nla_vrftable(struct seg6_local_lwt *a, struct seg6_local_lwt *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81fba270)
Location: net/ipv6/seg6_local.c:1383
Inline: False
```
**Symbols:**

```
ffffffff81fba270-ffffffff81fba28f: cmp_nla_vrftable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cmp_nla_vrftable(struct seg6_local_lwt *a, struct seg6_local_lwt *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8201a9a0)
Location: net/ipv6/seg6_local.c:1710
Inline: False
```
**Symbols:**

```
ffffffff8201a9a0-ffffffff8201a9bf: cmp_nla_vrftable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cmp_nla_vrftable(struct seg6_local_lwt *a, struct seg6_local_lwt *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff820e9960)
Location: net/ipv6/seg6_local.c:1771
Inline: False
```
**Symbols:**

```
ffffffff820e9960-ffffffff820e997f: cmp_nla_vrftable (STB_LOCAL)
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
