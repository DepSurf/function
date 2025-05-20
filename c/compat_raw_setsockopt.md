# Function: <code>compat_raw_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81784af0)
Location: net/ipv4/raw.c:833
Inline: False
```
**Symbols:**

```
ffffffff81784af0-ffffffff81784b47: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff817f2250)
Location: net/ipv4/raw.c:836
Inline: True
```
**Symbols:**

```
ffffffff817f2250-ffffffff817f228b: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81823030)
Location: net/ipv4/raw.c:840
Inline: True
```
**Symbols:**

```
ffffffff81823030-ffffffff8182306b: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81843b60)
Location: net/ipv4/raw.c:849
Inline: True
```
**Symbols:**

```
ffffffff81843b60-ffffffff81843b9d: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff818c4120)
Location: net/ipv4/raw.c:862
Inline: True
```
**Symbols:**

```
ffffffff818c4120-ffffffff818c415d: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81919db0)
Location: net/ipv4/raw.c:873
Inline: True
```
**Symbols:**

```
ffffffff81919db0-ffffffff81919ded: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81948620)
Location: net/ipv4/raw.c:865
Inline: True
```
**Symbols:**

```
ffffffff81948620-ffffffff8194865d: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819ac040)
Location: net/ipv4/raw.c:861
Inline: True
```
**Symbols:**

```
ffffffff819ac040-ffffffff819ac07f: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819e31e0)
Location: net/ipv4/raw.c:861
Inline: True
```
**Symbols:**

```
ffffffff819e31e0-ffffffff819e321f: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81ad0ac0)
Location: net/ipv4/raw.c:861
Inline: True
```
**Symbols:**

```
ffffffff81ad0ac0-ffffffff81ad0aff: compat_raw_setsockopt (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffff800010c970b8)
Location: net/ipv4/raw.c:861
Inline: True
```
**Symbols:**

```
ffff800010c970b8-ffff800010c97164: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (c000000000da9030)
Location: net/ipv4/raw.c:861
Inline: True
```
**Symbols:**

```
c000000000da9030-c000000000da90b8: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81983050)
Location: net/ipv4/raw.c:861
Inline: True
```
**Symbols:**

```
ffffffff81983050-ffffffff8198308f: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff8193cb10)
Location: net/ipv4/raw.c:861
Inline: True
```
**Symbols:**

```
ffffffff8193cb10-ffffffff8193cb4f: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819ed820)
Location: net/ipv4/raw.c:861
Inline: True
```
**Symbols:**

```
ffffffff819ed820-ffffffff819ed85f: compat_raw_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int compat_raw_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819f7710)
Location: net/ipv4/raw.c:861
Inline: True
```
**Symbols:**

```
ffffffff819f7710-ffffffff819f774f: compat_raw_setsockopt (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
