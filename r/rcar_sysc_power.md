# Function: <code>rcar_sysc_power</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int rcar_sysc_power(const struct rcar_sysc_ch *sysc_ch, bool on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/renesas/rcar-sysc.c (ffff80001081e1c0)
Location: drivers/soc/renesas/rcar-sysc.c:97
Inline: False
Direct callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_power_on
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_power_on
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_power_off
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_power_off
```
**Symbols:**

```
ffff80001081e1c0-ffff80001081e4d4: rcar_sysc_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rcar_sysc_power(const struct rcar_sysc_ch *sysc_ch, bool on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/renesas/rcar-sysc.c (c09385a8)
Location: drivers/soc/renesas/rcar-sysc.c:97
Inline: False
Direct callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power_cpu
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_power_on
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_power_off
```
**Symbols:**

```
c09385a8-c093881c: rcar_sysc_power (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
