# Function: <code>genradix_free_recurse</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8150e640)
Location: lib/generic-radix-tree.c:184
Inline: False
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:genradix_free_recurse
```
**Symbols:**

```
ffffffff8150e640-ffffffff8150e68c: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8152c780)
Location: lib/generic-radix-tree.c:204
Inline: False
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:genradix_free_recurse
```
**Symbols:**

```
ffffffff8152c780-ffffffff8152c7cc: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff815900f0)
Location: lib/generic-radix-tree.c:204
Inline: True
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
```
**Symbols:**

```
ffffffff815900f0-ffffffff815903fd: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff815acc60)
Location: lib/generic-radix-tree.c:204
Inline: True
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
```
**Symbols:**

```
ffffffff815acc60-ffffffff815acf6d: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff815b7bf8)
Location: lib/generic-radix-tree.c:204
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
```
**Symbols:**

```
ffffffff815b78d0-ffffffff815b7bdd: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8161e308)
Location: lib/generic-radix-tree.c:204
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
```
**Symbols:**

```
ffffffff8161dfe0-ffffffff8161e2ed: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff816ebf78)
Location: lib/generic-radix-tree.c:204
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
```
**Symbols:**

```
ffffffff816ebc00-ffffffff816ebf55: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff817dc718)
Location: lib/generic-radix-tree.c:204
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
```
**Symbols:**

```
ffffffff817dc390-ffffffff817dc6e5: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8181be2a)
Location: lib/generic-radix-tree.c:204
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
```
**Symbols:**

```
ffffffff8181b880-ffffffff8181bdf4: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff818613aa)
Location: lib/generic-radix-tree.c:274
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
```
**Symbols:**

```
ffffffff81860e00-ffffffff81861374: genradix_free_recurse (STB_LOCAL)
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
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffff8000106384c8)
Location: lib/generic-radix-tree.c:204
Inline: False
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:genradix_free_recurse
```
**Symbols:**

```
ffff8000106384c8-ffff800010638528: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (c07dde04)
Location: lib/generic-radix-tree.c:204
Inline: False
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:genradix_free_recurse
```
**Symbols:**

```
c07dde04-c07dde58: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (c0000000007dec20)
Location: lib/generic-radix-tree.c:204
Inline: False
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:genradix_free_recurse
```
**Symbols:**

```
c0000000007dec20-c0000000007decbc: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffe00046520e)
Location: lib/generic-radix-tree.c:204
Inline: False
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:genradix_free_recurse
```
**Symbols:**

```
ffffffe00046520e-ffffffe00046525c: genradix_free_recurse (STB_LOCAL)
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
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff81524d60)
Location: lib/generic-radix-tree.c:204
Inline: False
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:genradix_free_recurse
```
**Symbols:**

```
ffffffff81524d60-ffffffff81524dac: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff81515040)
Location: lib/generic-radix-tree.c:204
Inline: False
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:genradix_free_recurse
```
**Symbols:**

```
ffffffff81515040-ffffffff8151508c: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff81520df0)
Location: lib/generic-radix-tree.c:204
Inline: False
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:genradix_free_recurse
```
**Symbols:**

```
ffffffff81520df0-ffffffff81520e3c: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void genradix_free_recurse(struct genradix_node *n, unsigned int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8153a770)
Location: lib/generic-radix-tree.c:204
Inline: False
Direct callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:genradix_free_recurse
```
**Symbols:**

```
ffffffff8153a770-ffffffff8153a7bc: genradix_free_recurse (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
