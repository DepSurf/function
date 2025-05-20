# Function: <code>generic_add_lease</code>

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
In fs/locks.c (ffffffff81261fe6)
Location: fs/locks.c:1601
Inline: True
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
In fs/locks.c (ffffffff8128dfa2)
Location: fs/locks.c:1627
Inline: True
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
In fs/locks.c (ffffffff812a1eb5)
Location: fs/locks.c:1661
Inline: True
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
In fs/locks.c (ffffffff812b0c7d)
Location: fs/locks.c:1661
Inline: True
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
In fs/locks.c (ffffffff812d4723)
Location: fs/locks.c:1671
Inline: True
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
In fs/locks.c (ffffffff812fed2a)
Location: fs/locks.c:1669
Inline: True
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
In fs/locks.c (ffffffff81314773)
Location: fs/locks.c:1785
Inline: True
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
In fs/locks.c (ffffffff8133c0c6)
Location: fs/locks.c:1804
Inline: True
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
In fs/locks.c (ffffffff81354606)
Location: fs/locks.c:1832
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_add_lease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139b240)
Location: fs/locks.c:1835
Inline: False
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff8139b240-ffffffff8139b60a: generic_add_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_add_lease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813accb0)
Location: fs/locks.c:1836
Inline: False
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff813accb0-ffffffff813ad037: generic_add_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_add_lease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b4020)
Location: fs/locks.c:1839
Inline: False
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff813b4020-ffffffff813b43ab: generic_add_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_add_lease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81403d20)
Location: fs/locks.c:1742
Inline: False
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff81403d20-ffffffff814040ab: generic_add_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_add_lease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81479890)
Location: fs/locks.c:1717
Inline: False
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff81479890-ffffffff81479cba: generic_add_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_add_lease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150c230)
Location: fs/locks.c:1703
Inline: False
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff8150c230-ffffffff8150c65a: generic_add_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_add_lease(struct file *filp, long int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815439a0)
Location: fs/locks.c:1704
Inline: False
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff815439a0-ffffffff81543dd8: generic_add_lease (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_add_lease(struct file *filp, int arg, struct file_lock **flp, void **priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81578ea0)
Location: fs/locks.c:1718
Inline: False
Direct callers:
  - fs/locks.c:generic_setlease
```
**Symbols:**

```
ffffffff81578ea0-ffffffff815792b4: generic_add_lease (STB_LOCAL)
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
In fs/locks.c (ffff800010417480)
Location: fs/locks.c:1832
Inline: True
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
In fs/locks.c (c05e433c)
Location: fs/locks.c:1832
Inline: True
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
In fs/locks.c (c000000000527008)
Location: fs/locks.c:1832
Inline: True
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
In fs/locks.c (ffffffe0002bdd90)
Location: fs/locks.c:1832
Inline: True
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
In fs/locks.c (ffffffff8134cbe6)
Location: fs/locks.c:1832
Inline: True
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
In fs/locks.c (ffffffff8133d8c6)
Location: fs/locks.c:1832
Inline: True
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
In fs/locks.c (ffffffff8134a6b6)
Location: fs/locks.c:1832
Inline: True
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
In fs/locks.c (ffffffff8135ef64)
Location: fs/locks.c:1832
Inline: True
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int arg</code> ➡️ <code>int arg</code>
</li>
</ul>
</details>
</li>
</ul>
