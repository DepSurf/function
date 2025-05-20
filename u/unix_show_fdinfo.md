# Function: <code>unix_show_fdinfo</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unix_show_fdinfo(struct seq_file *m, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b236d0)
Location: net/unix/af_unix.c:686
Inline: False
```
**Symbols:**

```
ffffffff81b236d0-ffffffff81b236f7: unix_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unix_show_fdinfo(struct seq_file *m, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b320c0)
Location: net/unix/af_unix.c:684
Inline: False
```
**Symbols:**

```
ffffffff81b320c0-ffffffff81b320e7: unix_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unix_show_fdinfo(struct seq_file *m, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b1fde0)
Location: net/unix/af_unix.c:685
Inline: False
```
**Symbols:**

```
ffffffff81b1fde0-ffffffff81b1fe07: unix_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unix_show_fdinfo(struct seq_file *m, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81be4ba0)
Location: net/unix/af_unix.c:726
Inline: False
```
**Symbols:**

```
ffffffff81be4ba0-ffffffff81be4bc7: unix_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unix_show_fdinfo(struct seq_file *m, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d7c0b0)
Location: net/unix/af_unix.c:768
Inline: False
```
**Symbols:**

```
ffffffff81d7c0b0-ffffffff81d7c0ef: unix_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unix_show_fdinfo(struct seq_file *m, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f491b0)
Location: net/unix/af_unix.c:807
Inline: False
```
**Symbols:**

```
ffffffff81f491b0-ffffffff81f4926f: unix_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unix_show_fdinfo(struct seq_file *m, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81fa8d60)
Location: net/unix/af_unix.c:818
Inline: False
```
**Symbols:**

```
ffffffff81fa8d60-ffffffff81fa8e1e: unix_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unix_show_fdinfo(struct seq_file *m, struct socket *sock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff82076260)
Location: net/unix/af_unix.c:804
Inline: False
```
**Symbols:**

```
ffffffff82076260-ffffffff8207631e: unix_show_fdinfo (STB_LOCAL)
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
