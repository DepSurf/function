# Function: <code>cgroup_freeze_show</code>

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
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811521e0)
Location: kernel/cgroup/cgroup.c:3682
Inline: False
```
**Symbols:**

```
ffffffff811521e0-ffffffff81152231: cgroup_freeze_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115de30)
Location: kernel/cgroup/cgroup.c:3684
Inline: False
```
**Symbols:**

```
ffffffff8115de30-ffffffff8115de81: cgroup_freeze_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170920)
Location: kernel/cgroup/cgroup.c:3625
Inline: False
```
**Symbols:**

```
ffffffff81170920-ffffffff8117096e: cgroup_freeze_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116d430)
Location: kernel/cgroup/cgroup.c:3623
Inline: False
```
**Symbols:**

```
ffffffff8116d430-ffffffff8116d47f: cgroup_freeze_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116e0b0)
Location: kernel/cgroup/cgroup.c:3636
Inline: False
```
**Symbols:**

```
ffffffff8116e0b0-ffffffff8116e0ff: cgroup_freeze_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3713
Inline: False
```
**Symbols:**

```
ffffffff811943a0-ffffffff8119442d: cgroup_freeze_show (STB_LOCAL)
ffffffff81cb2e15-ffffffff81cb2e30: cgroup_freeze_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3724
Inline: False
```
**Symbols:**

```
ffffffff811c4e60-ffffffff811c4ef7: cgroup_freeze_show (STB_LOCAL)
ffffffff81e63c46-ffffffff81e63c61: cgroup_freeze_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3893
Inline: False
```
**Symbols:**

```
ffffffff812074a0-ffffffff81207537: cgroup_freeze_show (STB_LOCAL)
ffffffff8205c12a-ffffffff8205c145: cgroup_freeze_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3870
Inline: False
```
**Symbols:**

```
ffffffff8121cde0-ffffffff8121ce77: cgroup_freeze_show (STB_LOCAL)
ffffffff820da920-ffffffff820da93b: cgroup_freeze_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup.c (0)
Location: kernel/cgroup/cgroup.c:3924
Inline: False
```
**Symbols:**

```
ffffffff812348c0-ffffffff81234957: cgroup_freeze_show (STB_LOCAL)
ffffffff821b658a-ffffffff821b65a5: cgroup_freeze_show.cold (STB_LOCAL)
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
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101ce550)
Location: kernel/cgroup/cgroup.c:3684
Inline: False
```
**Symbols:**

```
ffff8000101ce550-ffff8000101ce5b8: cgroup_freeze_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0411ae4)
Location: kernel/cgroup/cgroup.c:3684
Inline: False
```
**Symbols:**

```
c0411ae4-c0411b3c: cgroup_freeze_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0000000002383b0)
Location: kernel/cgroup/cgroup.c:3684
Inline: False
```
**Symbols:**

```
c0000000002383b0-c000000000238428: cgroup_freeze_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000148ecc)
Location: kernel/cgroup/cgroup.c:3684
Inline: False
```
**Symbols:**

```
ffffffe000148ecc-ffffffe000148f26: cgroup_freeze_show (STB_LOCAL)
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
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156450)
Location: kernel/cgroup/cgroup.c:3684
Inline: False
```
**Symbols:**

```
ffffffff81156450-ffffffff811564a1: cgroup_freeze_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81149770)
Location: kernel/cgroup/cgroup.c:3684
Inline: False
```
**Symbols:**

```
ffffffff81149770-ffffffff811497c1: cgroup_freeze_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81154220)
Location: kernel/cgroup/cgroup.c:3684
Inline: False
```
**Symbols:**

```
ffffffff81154220-ffffffff81154271: cgroup_freeze_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_freeze_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161120)
Location: kernel/cgroup/cgroup.c:3684
Inline: False
```
**Symbols:**

```
ffffffff81161120-ffffffff81161171: cgroup_freeze_show (STB_LOCAL)
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
