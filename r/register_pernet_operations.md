# Function: <code>register_pernet_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817106e0)
Location: net/core/net_namespace.c:829
Inline: True
Direct callers:
  - net/core/net_namespace.c:register_pernet_subsys
  - net/core/net_namespace.c:register_pernet_device
```
**Symbols:**

```
ffffffff817106e0-ffffffff817108a8: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81778020)
Location: net/core/net_namespace.c:829
Inline: True
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff81778020-ffffffff817781e7: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817a5170)
Location: net/core/net_namespace.c:869
Inline: True
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff817a5170-ffffffff817a533c: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff817c33e0)
Location: net/core/net_namespace.c:935
Inline: True
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff817c33e0-ffffffff817c35a1: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8183cf30)
Location: net/core/net_namespace.c:937
Inline: True
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff8183cf30-ffffffff8183d0f1: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818877e0)
Location: net/core/net_namespace.c:998
Inline: True
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff818877e0-ffffffff818879a1: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818a8080)
Location: net/core/net_namespace.c:1112
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff818a8080-ffffffff818a8220: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818f3080)
Location: net/core/net_namespace.c:1199
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff818f3080-ffffffff818f3251: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81924fe0)
Location: net/core/net_namespace.c:1206
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff81924fe0-ffffffff819251b1: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f97b0)
Location: net/core/net_namespace.c:1204
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff819f97b0-ffffffff819f9850: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f8ff0)
Location: net/core/net_namespace.c:1208
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff819f8ff0-ffffffff819f9090: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819ddfd0)
Location: net/core/net_namespace.c:1201
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff819ddfd0-ffffffff819de199: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81a8e8a0)
Location: net/core/net_namespace.c:1203
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff81a8e8a0-ffffffff81a8eaa5: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81c047c0)
Location: net/core/net_namespace.c:1202
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff81c047c0-ffffffff81c049dd: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81db3ce0)
Location: net/core/net_namespace.c:1222
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
```
**Symbols:**

```
ffffffff81db3ce0-ffffffff81db3efd: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81e24390)
Location: net/core/net_namespace.c:1221
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
```
**Symbols:**

```
ffffffff81e24390-ffffffff81e245ad: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81ee25a0)
Location: net/core/net_namespace.c:1270
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:net_ns_init
  - net/core/net_namespace.c:net_defaults_init
```
**Symbols:**

```
ffffffff81ee25a0-ffffffff81ee27bd: register_pernet_operations (STB_LOCAL)
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
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffff800010bc0ad0)
Location: net/core/net_namespace.c:1206
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffff800010bc0ad0-ffff800010bc0cf4: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c0cdcdc0)
Location: net/core/net_namespace.c:1206
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
c0cdcdc0-c0cdcfc4: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (c000000000c9ae00)
Location: net/core/net_namespace.c:1206
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
c000000000c9ae00-c000000000c9b154: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffe00074e9c6)
Location: net/core/net_namespace.c:1206
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffe00074e9c6-ffffffe00074eb40: register_pernet_operations (STB_LOCAL)
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
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff818c4fe0)
Location: net/core/net_namespace.c:1206
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff818c4fe0-ffffffff818c51b1: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff8187ef20)
Location: net/core/net_namespace.c:1206
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff8187ef20-ffffffff8187f0f1: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff81915fe0)
Location: net/core/net_namespace.c:1206
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff81915fe0-ffffffff819161b1: register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819371e0)
Location: net/core/net_namespace.c:1206
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_device
  - net/core/net_namespace.c:register_pernet_subsys
```
**Symbols:**

```
ffffffff819371e0-ffffffff819373b1: register_pernet_operations (STB_LOCAL)
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
