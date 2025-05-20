# Function: <code>cond_bools_copy</code>

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
int cond_bools_copy(struct hashtab_node *new, struct hashtab_node *orig, void *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814eb3b0)
Location: security/selinux/ss/conditional.c:685
Inline: False
```
**Symbols:**

```
ffffffff814eb3b0-ffffffff814eb3f4: cond_bools_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cond_bools_copy(struct hashtab_node *new, struct hashtab_node *orig, void *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff814f2150)
Location: security/selinux/ss/conditional.c:685
Inline: False
```
**Symbols:**

```
ffffffff814f2150-ffffffff814f2194: cond_bools_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cond_bools_copy(struct hashtab_node *new, struct hashtab_node *orig, void *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff8154c8d0)
Location: security/selinux/ss/conditional.c:688
Inline: False
```
**Symbols:**

```
ffffffff8154c8d0-ffffffff8154c914: cond_bools_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cond_bools_copy(struct hashtab_node *new, struct hashtab_node *orig, void *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff815e57c0)
Location: security/selinux/ss/conditional.c:686
Inline: False
```
**Symbols:**

```
ffffffff815e57c0-ffffffff815e580e: cond_bools_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cond_bools_copy(struct hashtab_node *new, struct hashtab_node *orig, void *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff81694cd0)
Location: security/selinux/ss/conditional.c:686
Inline: False
```
**Symbols:**

```
ffffffff81694cd0-ffffffff81694d1e: cond_bools_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cond_bools_copy(struct hashtab_node *new, struct hashtab_node *orig, void *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff816cd1f0)
Location: security/selinux/ss/conditional.c:686
Inline: False
```
**Symbols:**

```
ffffffff816cd1f0-ffffffff816cd23e: cond_bools_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cond_bools_copy(struct hashtab_node *new, struct hashtab_node *orig, void *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/conditional.c (ffffffff817097d0)
Location: security/selinux/ss/conditional.c:686
Inline: False
```
**Symbols:**

```
ffffffff817097d0-ffffffff8170981e: cond_bools_copy (STB_LOCAL)
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
