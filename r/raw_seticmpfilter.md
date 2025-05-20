# Function: <code>raw_seticmpfilter</code>

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
In net/ipv4/raw.c (ffffffff81784b1e)
Location: net/ipv4/raw.c:784
Inline: True
Inline callers:
  - net/ipv4/raw.c:compat_raw_setsockopt
  - net/ipv4/raw.c:raw_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff817f21f0)
Location: net/ipv4/raw.c:787
Inline: False
```
**Symbols:**

```
ffffffff817f21f0-ffffffff817f224a: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81822fd0)
Location: net/ipv4/raw.c:791
Inline: False
```
**Symbols:**

```
ffffffff81822fd0-ffffffff8182302a: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81843b00)
Location: net/ipv4/raw.c:800
Inline: False
```
**Symbols:**

```
ffffffff81843b00-ffffffff81843b53: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff818c40c0)
Location: net/ipv4/raw.c:813
Inline: False
```
**Symbols:**

```
ffffffff818c40c0-ffffffff818c4113: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81919d50)
Location: net/ipv4/raw.c:824
Inline: False
```
**Symbols:**

```
ffffffff81919d50-ffffffff81919da3: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819485c0)
Location: net/ipv4/raw.c:816
Inline: False
```
**Symbols:**

```
ffffffff819485c0-ffffffff81948613: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819abfe0)
Location: net/ipv4/raw.c:812
Inline: False
```
**Symbols:**

```
ffffffff819abfe0-ffffffff819ac035: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819e3180)
Location: net/ipv4/raw.c:812
Inline: False
```
**Symbols:**

```
ffffffff819e3180-ffffffff819e31d5: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81ad0a60)
Location: net/ipv4/raw.c:812
Inline: False
```
**Symbols:**

```
ffffffff81ad0a60-ffffffff81ad0ab5: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81add380)
Location: net/ipv4/raw.c:813
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_setsockopt
```
**Symbols:**

```
ffffffff81add380-ffffffff81add3fc: raw_seticmpfilter (STB_LOCAL)
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
In net/ipv4/raw.c (ffffffff81ac70b5)
Location: net/ipv4/raw.c:813
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_setsockopt
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
In net/ipv4/raw.c (ffffffff81b858d5)
Location: net/ipv4/raw.c:816
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_setsockopt
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
In net/ipv4/raw.c (ffffffff81d16654)
Location: net/ipv4/raw.c:789
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81edc9e0)
Location: net/ipv4/raw.c:789
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_setsockopt
```
**Symbols:**

```
ffffffff81edc9e0-ffffffff81edca5d: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81f3b9c0)
Location: net/ipv4/raw.c:791
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_setsockopt
```
**Symbols:**

```
ffffffff81f3b9c0-ffffffff81f3ba3d: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, sockptr_t optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff82001ae0)
Location: net/ipv4/raw.c:790
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_setsockopt
```
**Symbols:**

```
ffffffff82001ae0-ffffffff82001b5d: raw_seticmpfilter (STB_LOCAL)
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
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffff800010c96f08)
Location: net/ipv4/raw.c:812
Inline: False
```
**Symbols:**

```
ffff800010c96f08-ffff800010c970b4: raw_seticmpfilter (STB_LOCAL)
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
In net/ipv4/raw.c (c0da5498)
Location: net/ipv4/raw.c:812
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (c000000000da8f90)
Location: net/ipv4/raw.c:812
Inline: False
```
**Symbols:**

```
c000000000da8f90-c000000000da9028: raw_seticmpfilter (STB_LOCAL)
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
In net/ipv4/raw.c (ffffffe0007f5dbc)
Location: net/ipv4/raw.c:812
Inline: True
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
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81982ff0)
Location: net/ipv4/raw.c:812
Inline: False
```
**Symbols:**

```
ffffffff81982ff0-ffffffff81983045: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff8193cab0)
Location: net/ipv4/raw.c:812
Inline: False
```
**Symbols:**

```
ffffffff8193cab0-ffffffff8193cb05: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819ed7c0)
Location: net/ipv4/raw.c:812
Inline: False
```
**Symbols:**

```
ffffffff819ed7c0-ffffffff819ed815: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int raw_seticmpfilter(struct sock *sk, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819f76b0)
Location: net/ipv4/raw.c:812
Inline: False
```
**Symbols:**

```
ffffffff819f76b0-ffffffff819f7705: raw_seticmpfilter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
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
