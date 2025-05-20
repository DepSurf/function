# Function: <code>__peernet2id_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8170fb40)
Location: net/core/net_namespace.c:180
Inline: False
Direct callers:
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:cleanup_net
```
**Symbols:**

```
ffffffff8170fb40-ffffffff8170fbcc: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81777470)
Location: net/core/net_namespace.c:180
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff81777470-ffffffff817774fc: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817a4470)
Location: net/core/net_namespace.c:185
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff817a4470-ffffffff817a44fc: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817c25e0)
Location: net/core/net_namespace.c:188
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff817c25e0-ffffffff817c2663: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8183c630)
Location: net/core/net_namespace.c:188
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff8183c630-ffffffff8183c6e3: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81886750)
Location: net/core/net_namespace.c:199
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff81886750-ffffffff818867d1: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818a6e40)
Location: net/core/net_namespace.c:199
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff818a6e40-ffffffff818a6ec1: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818f22d0)
Location: net/core/net_namespace.c:218
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff818f22d0-ffffffff818f2346: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81924220)
Location: net/core/net_namespace.c:218
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff81924220-ffffffff81924296: __peernet2id_alloc (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffff800010bbfbb0)
Location: net/core/net_namespace.c:218
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffff800010bbfbb0-ffff800010bbfc5c: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c0cdb638)
Location: net/core/net_namespace.c:218
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
c0cdb638-c0cdb6cc: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c000000000c98ef0)
Location: net/core/net_namespace.c:218
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
c000000000c98ef0-c000000000c98fe8: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffe00074d478)
Location: net/core/net_namespace.c:218
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffe00074d478-ffffffe00074d512: __peernet2id_alloc (STB_LOCAL)
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
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818c4220)
Location: net/core/net_namespace.c:218
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff818c4220-ffffffff818c4296: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8187e160)
Location: net/core/net_namespace.c:218
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff8187e160-ffffffff8187e1d6: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81915220)
Location: net/core/net_namespace.c:218
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff81915220-ffffffff81915296: __peernet2id_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __peernet2id_alloc(struct net *net, struct net *peer, bool *alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81936400)
Location: net/core/net_namespace.c:218
Inline: False
Direct callers:
  - net/core/net_namespace.c:rtnl_net_dumpid_one
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:peernet2id
  - net/core/net_namespace.c:peernet2id_alloc
  - net/core/net_namespace.c:peernet2id_alloc
```
**Symbols:**

```
ffffffff81936400-ffffffff81936476: __peernet2id_alloc (STB_LOCAL)
```
</details>
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
