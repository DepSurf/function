# Function: <code>bpf_iter_init_udp</code>

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
int bpf_iter_init_udp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ade840)
Location: net/ipv4/udp.c:3187
Inline: False
```
**Symbols:**

```
ffffffff81ade840-ffffffff81ade8c7: bpf_iter_init_udp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_iter_init_udp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ac9740)
Location: net/ipv4/udp.c:3258
Inline: False
```
**Symbols:**

```
ffffffff81ac9740-ffffffff81ac97c7: bpf_iter_init_udp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_iter_init_udp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b87fb0)
Location: net/ipv4/udp.c:3273
Inline: False
```
**Symbols:**

```
ffffffff81b87fb0-ffffffff81b88037: bpf_iter_init_udp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_iter_init_udp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d191b0)
Location: net/ipv4/udp.c:3288
Inline: False
```
**Symbols:**

```
ffffffff81d191b0-ffffffff81d19246: bpf_iter_init_udp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_iter_init_udp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81edf940)
Location: net/ipv4/udp.c:3416
Inline: False
```
**Symbols:**

```
ffffffff81edf940-ffffffff81edf9d6: bpf_iter_init_udp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bpf_iter_init_udp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f3fe50)
Location: net/ipv4/udp.c:3582
Inline: True
```
**Symbols:**

```
ffffffff81f3fe50-ffffffff81f3fea5: bpf_iter_init_udp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_iter_init_udp(void *priv_data, struct bpf_iter_aux_info *aux);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82005b10)
Location: net/ipv4/udp.c:3571
Inline: True
```
**Symbols:**

```
ffffffff82005b10-ffffffff82005b65: bpf_iter_init_udp (STB_LOCAL)
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
