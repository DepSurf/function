# Function: <code>mctp_getsockopt</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mctp_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/af_mctp.c (0)
Location: net/mctp/af_mctp.c:328
Inline: False
```
**Symbols:**

```
ffffffff81e36d50-ffffffff81e36e17: mctp_getsockopt (STB_LOCAL)
ffffffff81f10c82-ffffffff81f10c97: mctp_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mctp_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/af_mctp.c (0)
Location: net/mctp/af_mctp.c:329
Inline: False
```
**Symbols:**

```
ffffffff8200fe50-ffffffff8200ff17: mctp_getsockopt (STB_LOCAL)
ffffffff820b6f68-ffffffff820b6f7d: mctp_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mctp_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/af_mctp.c (0)
Location: net/mctp/af_mctp.c:329
Inline: False
```
**Symbols:**

```
ffffffff8208ca70-ffffffff8208cb37: mctp_getsockopt (STB_LOCAL)
ffffffff8213828f-ffffffff821382a4: mctp_getsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mctp_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/af_mctp.c (0)
Location: net/mctp/af_mctp.c:329
Inline: False
```
**Symbols:**

```
ffffffff82162f40-ffffffff82163007: mctp_getsockopt (STB_LOCAL)
ffffffff8221a12c-ffffffff8221a141: mctp_getsockopt.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
