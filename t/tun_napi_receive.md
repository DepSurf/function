# Function: <code>tun_napi_receive</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816fdc61)
Location: drivers/net/tun.c:237
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (ffffffff8173d346)
Location: drivers/net/tun.c:274
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (ffffffff817602c6)
Location: drivers/net/tun.c:280
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (ffffffff8179d962)
Location: drivers/net/tun.c:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (ffffffff817c1662)
Location: drivers/net/tun.c:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tun_napi_receive(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188e4e0)
Location: drivers/net/tun.c:240
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
```
**Symbols:**

```
ffffffff8188e4e0-ffffffff8188e662: tun_napi_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tun_napi_receive(struct napi_struct *napi, int budget);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189ca70)
Location: drivers/net/tun.c:211
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
```
**Symbols:**

```
ffffffff8189ca70-ffffffff8189cbf2: tun_napi_receive (STB_LOCAL)
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
In drivers/net/tun.c (ffffffff8187f6cf)
Location: drivers/net/tun.c:219
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (ffffffff8191083f)
Location: drivers/net/tun.c:225
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (ffffffff81a60da7)
Location: drivers/net/tun.c:225
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bebf67)
Location: drivers/net/tun.c:225
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c44417)
Location: drivers/net/tun.c:225
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cf9d07)
Location: drivers/net/tun.c:225
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (ffff8000109dc578)
Location: drivers/net/tun.c:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (c0ac1d08)
Location: drivers/net/tun.c:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (c000000000a9d388)
Location: drivers/net/tun.c:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (ffffffe00062710e)
Location: drivers/net/tun.c:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (ffffffff81786132)
Location: drivers/net/tun.c:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (ffffffff81765a82)
Location: drivers/net/tun.c:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (ffffffff817b64e2)
Location: drivers/net/tun.c:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
In drivers/net/tun.c (ffffffff817cf950)
Location: drivers/net/tun.c:270
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_poll
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
</ul>
