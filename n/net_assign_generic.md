# Function: <code>net_assign_generic</code>

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
In net/core/net_namespace.c (ffffffff8171050e)
Location: net/core/net_namespace.c:56
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff81777e4d)
Location: net/core/net_namespace.c:56
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff817a4f91)
Location: net/core/net_namespace.c:61
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff817c31f0)
Location: net/core/net_namespace.c:64
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff8183cd43)
Location: net/core/net_namespace.c:64
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff8188759c)
Location: net/core/net_namespace.c:76
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff818a7e42)
Location: net/core/net_namespace.c:76
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff818f2dec)
Location: net/core/net_namespace.c:84
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff81924d4c)
Location: net/core/net_namespace.c:84
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int net_assign_generic(struct net *net, unsigned int id, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f9250)
Location: net/core/net_namespace.c:98
Inline: False
Direct callers:
  - net/core/net_namespace.c:__register_pernet_operations
```
**Symbols:**

```
ffffffff819f9250-ffffffff819f9311: net_assign_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int net_assign_generic(struct net *net, unsigned int id, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f8d40)
Location: net/core/net_namespace.c:99
Inline: False
Direct callers:
  - net/core/net_namespace.c:__register_pernet_operations
```
**Symbols:**

```
ffffffff819f8d40-ffffffff819f8e01: net_assign_generic (STB_LOCAL)
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
In net/core/net_namespace.c (ffffffff819ddf41)
Location: net/core/net_namespace.c:87
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff81a8e561)
Location: net/core/net_namespace.c:87
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff81c0449a)
Location: net/core/net_namespace.c:81
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int net_assign_generic(struct net *net, unsigned int id, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81db3b40)
Location: net/core/net_namespace.c:81
Inline: False
Direct callers:
  - net/core/net_namespace.c:ops_init
```
**Symbols:**

```
ffffffff81db3b40-ffffffff81db3bd4: net_assign_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int net_assign_generic(struct net *net, unsigned int id, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81e241f0)
Location: net/core/net_namespace.c:82
Inline: False
Direct callers:
  - net/core/net_namespace.c:ops_init
```
**Symbols:**

```
ffffffff81e241f0-ffffffff81e24282: net_assign_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int net_assign_generic(struct net *net, unsigned int id, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81ee2150)
Location: net/core/net_namespace.c:82
Inline: False
Direct callers:
  - net/core/net_namespace.c:ops_init
```
**Symbols:**

```
ffffffff81ee2150-ffffffff81ee21e2: net_assign_generic (STB_LOCAL)
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
In net/core/net_namespace.c (ffff800010bc0834)
Location: net/core/net_namespace.c:84
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (c0cdcb3c)
Location: net/core/net_namespace.c:84
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (c000000000c9aa7c)
Location: net/core/net_namespace.c:84
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffe00074e7a2)
Location: net/core/net_namespace.c:84
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff818c4d4c)
Location: net/core/net_namespace.c:84
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff8187ec8c)
Location: net/core/net_namespace.c:84
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff81915d4c)
Location: net/core/net_namespace.c:84
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
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
In net/core/net_namespace.c (ffffffff81936f4c)
Location: net/core/net_namespace.c:84
Inline: True
Inline callers:
  - net/core/net_namespace.c:ops_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
