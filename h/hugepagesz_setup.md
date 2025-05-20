# Function: <code>hugepagesz_setup</code>

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
int hugepagesz_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff82cfe09d)
Location: mm/hugetlb.c:3383
Inline: False
```
**Symbols:**

```
ffffffff82cfe09d-ffffffff82cfe193: hugepagesz_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hugepagesz_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff82feaa90)
Location: mm/hugetlb.c:3337
Inline: False
```
**Symbols:**

```
ffffffff82feaa90-ffffffff82feab86: hugepagesz_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hugepagesz_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff831f5405)
Location: mm/hugetlb.c:3506
Inline: False
```
**Symbols:**

```
ffffffff831f5405-ffffffff831f54fa: hugepagesz_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hugepagesz_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff832db808)
Location: mm/hugetlb.c:3792
Inline: False
```
**Symbols:**

```
ffffffff832db808-ffffffff832db91f: hugepagesz_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hugepagesz_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff83490edc)
Location: mm/hugetlb.c:4240
Inline: False
```
**Symbols:**

```
ffffffff83490edc-ffffffff83490fef: hugepagesz_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hugepagesz_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff83ec2e30)
Location: mm/hugetlb.c:4423
Inline: False
```
**Symbols:**

```
ffffffff83ec2e30-ffffffff83ec305e: hugepagesz_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hugepagesz_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff836e7f10)
Location: mm/hugetlb.c:4460
Inline: False
```
**Symbols:**

```
ffffffff836e7f10-ffffffff836e813e: hugepagesz_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hugepagesz_setup(char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8391b430)
Location: mm/hugetlb.c:4718
Inline: False
```
**Symbols:**

```
ffffffff8391b430-ffffffff8391b65e: hugepagesz_setup (STB_LOCAL)
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
