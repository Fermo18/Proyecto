# Next Steps

{% hint style="success" %}
:tada: Congrats! You've finished the primary steps of setting up your validator. You're now an Ethereum staker!
{% endhint %}

## :track\_next: FAQ

<details>

<summary>Wen staking rewards?</summary>

**Activation Queue**: Once your EL+CL is synced, validator up and running, you just wait for activation. This process can take 24+ hours. Only 900 new validators can join per day. Check the queue length: [https://wenmerge.com ](https://wenmerge.com)

**Activated**: When you're activated, your validator will begin creating and voting on blocks while earning staking rewards.

**Quick monitoring**: Use [https://holesky.beaconcha.in](https://holesky.beaconcha.in/) to create alerts and track your validator's performance.

</details>

<details>

<summary>Sync Timeline</summary>

Syncing the consensus client is instantaneous with checkpoint sync but the execution client can take up to a day. On nodes with fast NVME drives and gigabit internet, expect your node to be fully synced in a few hours.



**¿Cómo sé que estoy completamente sincronizado?**

* Compruebe los registros de su cliente de ejecución y compare el número de bloque con el bloque más reciente en [https://holesky.etherscan.io](https://holesky.etherscan.io/)
  * Compruebe los registros EL: `journalctl -fu execution`
* Gracias a la sincronización de puntos de control, el de su cliente de consenso se sincroniza al instante. Puede comparar el número de tragamonedas con la tragamonedas más reciente en [https://holesky.beaconcha.in](https://holesky.beaconcha.in/)
  * Compruebe los registros de CL: `journalctl -fu consensus`



</details>

### :pulgar arriba: Pasos recomendados

{% hint style="info" %}
:píldora:**Instalar** [**EthPillar**](../../ethpillar.md):¡Una sencilla interfaz de usuario complementaria para la gestión de nodos! El uso de la línea de comandos se reduce considerablemente. Actualice su software con una pulsación de tecla.

![](../../../../.gitbook/assets/ethpillar.png)
{% insinuación final %}

* :newspaper2:**Suscríbete al repositorio de Github de tu cliente de Ejecución y cliente de Consenso**: Recibe notificaciones de nuevas versiones. Encuentre los enlaces de Github en cada sección de descripción general EL/CL's. En la página de Github de su EL o CL mientras está conectado,hada clic en el botón **Watch** button > **Custom** > click the checkbox for "**Release**".
* :sonreír:**Únete a la comunidad**:  [Únete a la comunidad en Discord y Reddit](../../guide-or-how-to-setup-a-validator-on-eth2-mainnet/joining-the-community-on-discord-and-reddit.md#discord) para discutir todo lo relacionado con el staking.
* :tools:*Mantenimiento** **Nodos**: Familiarize yourself with [Part II - Maintenance](../../guide-or-how-to-setup-a-validator-on-eth2-mainnet/part-ii-maintenance/) section, as you'll need to keep your staking node running at its best.
* :books:**Study** [**EthStaker Knowledge Base**](https://docs.ethstaker.cc/ethstaker-knowledge-base/): Increase your staking understanding
* :cd:**Backups**: Review your staking validator backups!
* :fingers\_crossed:**Finished testing?** Before decommissioning your validator, it's good practice to properly [exit your validator](../../guide-or-how-to-setup-a-validator-on-eth2-mainnet/part-iii-tips/voluntary-exiting-a-validator.md) as this improves staking network health.

### :checkered\_flag: Optional Steps

* :robot:**MEV-boost**: Setup [MEV-boost](../../mev-boost/) for extra staking rewards!
* :bar\_chart:**Monitoring**: Setup [Monitoring with Grafana and Prometheus](../../guide-or-how-to-setup-a-validator-on-eth2-mainnet/part-i-installation/monitoring-your-validator-with-grafana-and-prometheus.md)
* :chains:**RPC**: Setup using your own [Node as a RPC endpoint](../../guide-or-how-to-setup-a-validator-on-eth2-mainnet/part-iii-tips/using-staking-node-as-rpc-url-endpoint.md).
* :mobile\_phone:**Notifications**: Setup [Mobile App Notifications and Monitoring by beaconcha.in](../../guide-or-how-to-setup-a-validator-on-eth2-mainnet/part-i-installation/mobile-app-node-monitoring-by-beaconchain.md)
* :up:**External Monitoring**: Setup [External Monitoring with Uptime Check by Google Cloud](../../archived-guides/guide-or-how-to-setup-a-validator-on-eth2-mainnet/part-i-installation/monitoring-with-uptime-check-by-google-cloud.md)
* :books:**Knowledge**: Familiarize yourself with [Part III - Tips](../../guide-or-how-to-setup-a-validator-on-eth2-mainnet/part-iii-tips/) section, as you dive deeper into staking.

### :telephone: **Need extra live support?**

* Find Ethstaker frens on the [Ethstaker](https://discord.io/ethstaker) Discord and [coincashew](https://discord.gg/dEpAVWgFNB) Discord.
* Use reddit: [r/Ethstaker](https://www.reddit.com/r/ethstaker/), or [DMs](https://www.reddit.com/user/coincashew), or [r/coincashew](https://www.reddit.com/r/coincashew/)

### :heart\_decoration: Like these guides?

* **Audience-funded guide**: If you found this helpful, [please consider supporting it directly.](../../../../donations.md) :pray:
* **Support us on Gitcoin Grants:** We build this guide exclusively by community support!
* **Feedback or pull-requests**: [https://github.com/coincashew/coincashew](https://github.com/coincashew/coincashew)

{% hint style="success" %}
#### Ready for mainnet staking? [**Mainnet guide available here.**](../../guide-or-how-to-setup-a-validator-on-eth2-mainnet/)
{% endhint %}

## Last Words

> I stand upon the shoulders of giants and as such, invite you to stand upon mine. Use my work with or without attribution; I make no claim of "intellectual property." My ideas are the result of countless millenia of evolution - they belong to humanity.

<figure><img src="../../../../.gitbook/assets/leslie-solo.png" alt=""><figcaption><p>This is Leslie, the official mascot of Eth Staking</p></figcaption></figure>
