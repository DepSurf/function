# Function: <code>ops_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81710480)
Location: net/core/net_namespace.c:93
Inline: False
Direct callers:
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff81710480-ffffffff8171059f: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81777dd0)
Location: net/core/net_namespace.c:93
Inline: False
Direct callers:
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff81777dd0-ffffffff81777ed8: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817a4f10)
Location: net/core/net_namespace.c:99
Inline: False
Direct callers:
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff817a4f10-ffffffff817a5023: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817c3160)
Location: net/core/net_namespace.c:102
Inline: False
Direct callers:
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff817c3160-ffffffff817c3288: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8183ccb0)
Location: net/core/net_namespace.c:102
Inline: False
Direct callers:
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff8183ccb0-ffffffff8183cddb: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81887520)
Location: net/core/net_namespace.c:113
Inline: False
Direct callers:
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff81887520-ffffffff81887617: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818a7dc0)
Location: net/core/net_namespace.c:113
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff818a7dc0-ffffffff818a7eba: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818f2d70)
Location: net/core/net_namespace.c:121
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff818f2d70-ffffffff818f2e6f: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81924cd0)
Location: net/core/net_namespace.c:121
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff81924cd0-ffffffff81924dcf: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f9638)
Location: net/core/net_namespace.c:135
Inline: True
Inline callers:
  - net/core/net_namespace.c:__register_pernet_operations
Direct callers:
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff819f9320-ffffffff819f93ba: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f8e78)
Location: net/core/net_namespace.c:136
Inline: True
Inline callers:
  - net/core/net_namespace.c:__register_pernet_operations
Direct callers:
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff819f9140-ffffffff819f91da: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819ddec0)
Location: net/core/net_namespace.c:124
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff819ddec0-ffffffff819ddfc4: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81a8e4e0)
Location: net/core/net_namespace.c:124
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff81a8e4e0-ffffffff81a8e5e4: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81c04410)
Location: net/core/net_namespace.c:118
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff81c04410-ffffffff81c0451b: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81db3bf0)
Location: net/core/net_namespace.c:118
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff81db3bf0-ffffffff81db3cc3: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81e242a0)
Location: net/core/net_namespace.c:119
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff81e242a0-ffffffff81e24373: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81ee2200)
Location: net/core/net_namespace.c:119
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff81ee2200-ffffffff81ee22d3: ops_init (STB_LOCAL)
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
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffff800010bc0798)
Location: net/core/net_namespace.c:121
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffff800010bc0798-ffff800010bc08c0: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c0cdcab4)
Location: net/core/net_namespace.c:121
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
c0cdcab4-c0cdcbb4: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c000000000c9a990)
Location: net/core/net_namespace.c:121
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
c000000000c9a990-c000000000c9ab4c: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffe00074e72a)
Location: net/core/net_namespace.c:121
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffe00074e72a-ffffffe00074e81c: ops_init (STB_LOCAL)
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
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818c4cd0)
Location: net/core/net_namespace.c:121
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff818c4cd0-ffffffff818c4dcf: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8187ec10)
Location: net/core/net_namespace.c:121
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff8187ec10-ffffffff8187ed0f: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81915cd0)
Location: net/core/net_namespace.c:121
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff81915cd0-ffffffff81915dcf: ops_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ops_init(const struct pernet_operations *ops, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81936ed0)
Location: net/core/net_namespace.c:121
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
  - net/core/net_namespace.c:setup_net
```
**Symbols:**

```
ffffffff81936ed0-ffffffff81936fcf: ops_init (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
