# Function: <code>mctp_dev_release_key</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void mctp_dev_release_key(struct mctp_dev *dev, struct mctp_sk_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff81e38ad0)
Location: net/mctp/device.c:322
Inline: False
Direct callers:
  - net/mctp/route.c:__mctp_key_done_in
```
**Symbols:**

```
ffffffff81e38ad0-ffffffff81e38b28: mctp_dev_release_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mctp_dev_release_key(struct mctp_dev *dev, struct mctp_sk_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff82011da0)
Location: net/mctp/device.c:322
Inline: False
Direct callers:
  - net/mctp/route.c:__mctp_key_done_in
```
**Symbols:**

```
ffffffff82011da0-ffffffff82011df8: mctp_dev_release_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mctp_dev_release_key(struct mctp_dev *dev, struct mctp_sk_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff8208eb80)
Location: net/mctp/device.c:322
Inline: False
Direct callers:
  - net/mctp/route.c:__mctp_key_done_in
```
**Symbols:**

```
ffffffff8208eb80-ffffffff8208ebd8: mctp_dev_release_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mctp_dev_release_key(struct mctp_dev *dev, struct mctp_sk_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff82165070)
Location: net/mctp/device.c:322
Inline: False
Direct callers:
  - net/mctp/route.c:__mctp_key_done_in
```
**Symbols:**

```
ffffffff82165070-ffffffff821650c8: mctp_dev_release_key (STB_GLOBAL)
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
