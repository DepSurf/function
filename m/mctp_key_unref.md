# Function: <code>mctp_key_unref</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mctp_key_unref(struct mctp_sk_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff81e39e50)
Location: net/mctp/route.c:154
Inline: True
Direct callers:
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
```
**Symbols:**

```
ffffffff81e39e50-ffffffff81e39ee3: mctp_key_unref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mctp_key_unref(struct mctp_sk_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82013460)
Location: net/mctp/route.c:155
Inline: True
Direct callers:
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
```
**Symbols:**

```
ffffffff82013460-ffffffff8201353a: mctp_key_unref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mctp_key_unref(struct mctp_sk_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff82090280)
Location: net/mctp/route.c:155
Inline: True
Direct callers:
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
```
**Symbols:**

```
ffffffff82090280-ffffffff8209035a: mctp_key_unref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mctp_key_unref(struct mctp_sk_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mctp/route.c (ffffffff821667c0)
Location: net/mctp/route.c:155
Inline: True
Direct callers:
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/af_mctp.c:mctp_ioctl
  - net/mctp/route.c:mctp_local_output
  - net/mctp/route.c:mctp_alloc_local_tag
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:mctp_route_input
  - net/mctp/route.c:__mctp_key_done_in
  - net/mctp/route.c:__mctp_key_done_in
```
**Symbols:**

```
ffffffff821667c0-ffffffff8216689a: mctp_key_unref (STB_GLOBAL)
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
