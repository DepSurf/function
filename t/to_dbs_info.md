# Function: <code>to_dbs_info</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: drivers/cpufreq/cpufreq_ondemand.h:22
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: drivers/cpufreq/cpufreq_conservative.c:22
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: drivers/cpufreq/cpufreq_ondemand.h:22
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: drivers/cpufreq/cpufreq_conservative.c:23
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: drivers/cpufreq/cpufreq_ondemand.h:22
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: drivers/cpufreq/cpufreq_conservative.c:23
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: drivers/cpufreq/cpufreq_ondemand.h:22
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: drivers/cpufreq/cpufreq_conservative.c:23
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818245b9)
Location: drivers/cpufreq/cpufreq_ondemand.h:22
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818253a9)
Location: drivers/cpufreq/cpufreq_conservative.c:23
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81850479)
Location: drivers/cpufreq/cpufreq_ondemand.h:22
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81851269)
Location: drivers/cpufreq/cpufreq_conservative.c:23
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818939a9)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81894789)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818c59c9)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818c67a9)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81997b39)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81998969)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8199ac59)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff8199ba49)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8197f919)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81980709)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81a28ab9)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81a298a9)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffff800010b2390c)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffff800010b2495c)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (c0bfda90)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (c0bfe944)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (c000000000c1804c)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (c000000000c1949c)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
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
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff8186a0e9)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff8186aec9)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81832d99)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81833b79)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818bae79)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818bbc59)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff818d7149)
Location: drivers/cpufreq/cpufreq_ondemand.h:19
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_start
  - drivers/cpufreq/cpufreq_ondemand.c:od_free
  - drivers/cpufreq/cpufreq_ondemand.c:store_powersave_bias
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:od_dbs_update
  - drivers/cpufreq/cpufreq_ondemand.c:generic_powersave_bias_target
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff818d7f49)
Location: drivers/cpufreq/cpufreq_conservative.c:20
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_start
  - drivers/cpufreq/cpufreq_conservative.c:cs_free
  - drivers/cpufreq/cpufreq_conservative.c:cs_dbs_update
```
</details>
</li>
</ul>

## Differences
