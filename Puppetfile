#
forge 'http://forge.puppetlabs.com'

def default_branch(default)
  begin
    match = /(.+)_(cdpe|cdpe_ia)_\d+$/.match(@librarian.environment.name)
    match ? match[1]:default
  rescue
    default
  end
end

# Modules from the Puppet Forge
# Versions should be updated to be the latest at the time you start
mod 'puppetlabs-acl', '3.1.1'
mod 'puppetlabs-apache', '5.4.0'
mod 'puppetlabs-apt', '7.4.2'
mod 'puppetlabs-aws', '2.1.0'
mod 'puppetlabs-azure', '1.3.1'
mod 'puppetlabs-bolt_shim', '0.3.0'
mod 'puppetlabs-cd4pe', '3.0.0'
mod 'puppetlabs-cd4pe_jobs', '1.5.0'
mod 'puppetlabs-chocolatey', '5.0.2'
mod 'puppetlabs-cisco_ios', '1.2.0'
mod 'puppetlabs-ciscopuppet', '2.1.0'
mod 'puppetlabs-concat', '6.2.0'
mod 'puppetlabs-device_manager', '3.0.1'
mod 'puppetlabs-dism', '1.3.1'
mod 'puppetlabs-docker', '3.10.0'
mod 'puppetlabs-dsc', '1.9.4'
mod 'puppetlabs-exec', '0.7.0'
mod 'puppetlabs-facter_task', '0.7.0'
mod 'puppetlabs-firewall', '2.4.0'
mod 'puppetlabs-gcc', '0.3.0'
mod 'puppetlabs-git', '0.5.0'
mod 'puppetlabs-haproxy', '4.2.1'
mod 'puppetlabs-hocon', '1.1.0'
mod 'puppetlabs-iis', '7.0.1'
mod 'puppetlabs-inifile', '4.2.0'
mod 'puppetlabs-java', '6.2.0'
mod 'puppetlabs-limits', '0.1.0'
mod 'puppetlabs-motd', '4.1.1'
mod 'puppetlabs-mount_iso', '3.0.0'
mod 'puppetlabs-mysql', '10.5.0'
mod 'puppetlabs-netdev_stdlib', '0.23.0'
mod 'puppetlabs-ntp', '8.3.0'
mod 'puppetlabs-panos', '1.2.1'
mod 'puppetlabs-pipelines', '1.0.1'
mod 'puppetlabs-powershell', '3.0.1'
mod 'puppetlabs-puppet_authorization', '0.5.1'
mod 'puppetlabs-puppetserver_gem', '1.1.1'
mod 'puppetlabs-pwshlib', '0.4.1'
mod 'puppetlabs-reboot', '3.0.0'
mod 'puppetlabs-registry', '3.1.0'
mod 'puppetlabs-resource', '1.1.0'
mod 'puppetlabs-resource_api', '1.1.0'
mod 'puppetlabs-service', '1.2.0'
mod 'puppetlabs-splunk_hec', '0.8.1'
mod 'puppetlabs-sqlserver', '2.6.2'
mod 'puppetlabs-stdlib', '6.3.0'
mod 'puppetlabs-tomcat', '4.0.0'
mod 'puppetlabs-transition', '0.1.3'
mod 'puppetlabs-translate', '2.2.0'
mod 'puppetlabs-vcsrepo', '3.1.0'

# Forge Community Modules
mod 'WhatsARanjit-diskspace', '0.2.0'
mod 'WhatsARanjit-node_manager', '0.7.3'
mod 'abuxton-pdk', '0.2.2'
mod 'ajjahn-samba', '0.5.0'
mod 'andulla-vsphere_conf', '0.0.9'
mod 'aristanetworks-eos', '1.5.0'
mod 'aristanetworks-netdev_stdlib_eos', '1.2.0'
mod 'ayohrling-local_security_policy', '0.6.3'
mod 'biemond-wildfly', '2.3.2'
mod 'bodgit-rngd', '2.0.3'
mod 'camptocamp-systemd', '2.9.0'
mod 'computology-packagecloud', '0.3.2'
mod 'crayfishx-purge', '1.2.1'
mod 'cyberious-windows_java', '1.0.2'
mod 'fervid-auditpol', '1.0.1'
mod 'ghoneycutt-ssh', '3.61.0'
mod 'herculesteam-augeasproviders_core', '2.6.0'
mod 'herculesteam-augeasproviders_ssh', '3.3.0'
mod 'herculesteam-augeasproviders_sysctl', '2.5.0'
mod 'hunner-wordpress', '1.0.0'
mod 'ipcrm-echo', '0.1.6'
mod 'jdowning-rbenv', '2.5.0'
mod 'jpadams-puppet_vim_env', '2.4.0' # There is a bug in 2.4.1
mod 'jriviere-windows_ad', '0.3.2'
mod 'kogitoapp-gitea', '1.0.4'
mod 'lwf-remote_file', '1.1.3'
mod 'nexcess-auditd', '2.0.0'
mod 'puppet-archive', '4.5.0'
mod 'puppet-epel', '3.0.1'
mod 'puppet-gitlab', '5.0.0'
mod 'puppet-hiera', '4.0.0'
mod 'puppet-jenkins', '2.0.0'
mod 'puppet-nginx', '1.1.0'
mod 'puppet-php', '7.1.0'
mod 'puppet-python', '4.1.1'
mod 'puppet-rabbitmq', '10.0.1'
mod 'puppet-redis', '6.0.0'
mod 'puppet-selinux', '3.2.0'
mod 'puppet-splunk', '8.0.0'
mod 'puppet-wget', '2.0.1'
mod 'puppet-windows_env', '4.0.0'
mod 'puppet-windows_firewall', '2.0.2'
mod 'puppet-windowsfeature', '3.2.2'
mod 'puppetlabs-augeas_core', '1.0.5'
mod 'puppetlabs-host_core', '1.0.3'
mod 'puppetlabs-selinux_core', '1.0.4'
mod 'puppetlabs-sshkeys_core', '2.0.0'
mod 'puppetlabs-yumrepo_core', '1.0.7'
mod 'puppet-yum', '4.3.0'
mod 'reidmv-unzip', '0.1.2'
mod 'sensu-sensu', '4.10.0'
mod 'thias-sysctl', '1.0.6'
mod 'tkishel-system_gem', '1.1.1'
mod 'trlinkin-domain_membership', '1.1.2'
mod 'tse-time', '1.0.1'
mod 'tse-winntp', '1.0.1'
mod 'yelp-uchiwa', '2.1.0'

mod 'demo_cis',
    git: 'https://github.com/ipcrm/ipcrm-demo_cis.git',
    ref: '4e6b63b'

mod 'rgbank',
    git:            'https://github.com/puppetlabs-seteam/puppetlabs-rgbank.git',
    branch:         :control_branch,
    default_branch: default_branch('master')

mod 'netstat',
    git: 'https://github.com/ipcrm/ipcrm-netstat.git',
    ref: '64bcee0'
    
#modified  a few things
mod 'secteam_cis',
    git: 'https://github.com/ssorb/se_secteam_cis.git',
    branch: 'master'
