<!---
This is an autogenerated file!

Please do not edit this file directly, but instead make changes to the
sigs.yaml file in the project root.

To understand how this file is generated, see https://git.k8s.io/community/generator/README.md
--->
# Cloud Provider Special Interest Group

Ensures that the Kubernetes ecosystem is evolving in a way that is neutral to all (public and private) cloud providers. It will be responsible for establishing standards and requirements that must be met by all providers to ensure optimal integration with Kubernetes.

The [charter](CHARTER.md) defines the scope and governance of the Cloud Provider Special Interest Group.

## Meetings
*Joining the [mailing list](https://groups.google.com/forum/#!forum/kubernetes-sig-cloud-provider) for the group will typically add invites for the following meetings to your calendar.*
* Regular SIG Meeting: [Wednesdays at 9:00 PT (Pacific Time)](https://zoom.us/j/508079177?pwd=ZmEvMksxdTFTc0N1eXFLRm91QUlyUT09) (biweekly). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=9%3A00&tz=PT%20%28Pacific%20Time%29).
  * [Meeting notes and Agenda](https://docs.google.com/document/d/1OZE-ub-v6B8y-GuaWejL-vU_f9jsjBbrim4LtTfxssw/edit#heading=h.w7i4ksrweimp).
  * [Meeting recordings](https://www.youtube.com/playlist?list=PL69nYSiGNLP3dXLcYbRKCbpPCN-8CDFAB).

## Leadership

### Chairs
The Chairs of the SIG run operations and processes governing the SIG.

* Bridget Kromhout (**[@bridgetkromhout](https://github.com/bridgetkromhout)**), Microsoft
* Michael McCune (**[@elmiko](https://github.com/elmiko)**), Red Hat

### Technical Leads
The Technical Leads of the SIG establish new subprojects, decommission existing
subprojects, and resolve cross-subproject technical issues and decisions.

* Walter Fender (**[@cheftako](https://github.com/cheftako)**), Google
* Michael McCune (**[@elmiko](https://github.com/elmiko)**), Red Hat
* Joel Speed (**[@joelspeed](https://github.com/joelspeed)**), Red Hat

## Emeritus Leads

* Andrew Sy Kim (**[@andrewsykim](https://github.com/andrewsykim)**)
* Chris Hoge (**[@hogepodge](https://github.com/hogepodge)**)
* Jago Macleod (**[@jagosan](https://github.com/jagosan)**)
* Nick Turner (**[@nckturner](https://github.com/nckturner)**)

## Contact
- Slack: [#sig-cloud-provider](https://kubernetes.slack.com/messages/sig-cloud-provider)
- [Mailing list](https://groups.google.com/forum/#!forum/kubernetes-sig-cloud-provider)
- [Open Community Issues/PRs](https://github.com/kubernetes/community/labels/sig%2Fcloud-provider)
- GitHub Teams:
    - [@kubernetes/sig-cloud-provider-api-reviews](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-api-reviews) - API Changes and Reviews
    - [@kubernetes/sig-cloud-provider-bugs](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-bugs) - Bug Triage and Troubleshooting
    - [@kubernetes/sig-cloud-provider-feature-requests](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-feature-requests) - Feature Requests
    - [@kubernetes/sig-cloud-provider-maintainers](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-maintainers) - Cloud Providers Maintainers
    - [@kubernetes/sig-cloud-provider-pr-reviews](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-pr-reviews) - PR Reviews
    - [@kubernetes/sig-cloud-provider-proposals](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-proposals) - Design Proposals
    - [@kubernetes/sig-cloud-provider-test-failures](https://github.com/orgs/kubernetes/teams/sig-cloud-provider-test-failures) - Test Failures and Triage
    - [@kubernetes/sig-cloud-providers-misc](https://github.com/orgs/kubernetes/teams/sig-cloud-providers-misc) - General Discussion
- Steering Committee Liaison: Maciej Szulik (**[@soltysh](https://github.com/soltysh)**)

## Working Groups

The following [working groups][working-group-definition] are sponsored by sig-cloud-provider:
* [WG Node Lifecycle](/wg-node-lifecycle)
* [WG Structured Logging](/wg-structured-logging)


## Subprojects

The following [subprojects][subproject-definition] are owned by sig-cloud-provider:
### cloud-provider-extraction-migration
- **Owners:**
  - [kubernetes-sigs/apiserver-network-proxy](https://github.com/kubernetes-sigs/apiserver-network-proxy/blob/master/OWNERS)
  - [kubernetes-sigs/cloud-pv-admission-labeler](https://github.com/kubernetes-sigs/cloud-pv-admission-labeler/blob/main/OWNERS)
  - [kubernetes/community/sig-cloud-provider/cloud-provider-extraction-migration](https://github.com/kubernetes/community/blob/master/sig-cloud-provider/cloud-provider-extraction-migration/OWNERS)
  - [kubernetes/legacy-cloud-providers](https://github.com/kubernetes/legacy-cloud-providers/blob/master/OWNERS)
### kubernetes-cloud-provider
- **Owners:**
  - [kubernetes/cloud-provider-sample](https://github.com/kubernetes/cloud-provider-sample/blob/master/OWNERS)
  - [kubernetes/cloud-provider](https://github.com/kubernetes/cloud-provider/blob/master/OWNERS)
  - [kubernetes/kubernetes/cmd/cloud-controller-manager](https://github.com/kubernetes/kubernetes/blob/master/cmd/cloud-controller-manager/OWNERS)
  - [kubernetes/kubernetes/pkg/cloudprovider](https://github.com/kubernetes/kubernetes/blob/master/pkg/cloudprovider/OWNERS)
  - [kubernetes/kubernetes/pkg/controller/cloud](https://github.com/kubernetes/kubernetes/blob/master/pkg/controller/cloud/OWNERS)
  - [kubernetes/kubernetes/staging/src/k8s.io/cloud-provider](https://github.com/kubernetes/kubernetes/blob/master/staging/src/k8s.io/cloud-provider/OWNERS)
### provider-alibaba-cloud
- **Owners:**
  - [kubernetes-sigs/alibaba-cloud-csi-driver](https://github.com/kubernetes-sigs/alibaba-cloud-csi-driver/blob/master/OWNERS)
  - [kubernetes/cloud-provider-alibaba-cloud](https://github.com/kubernetes/cloud-provider-alibaba-cloud/blob/master/OWNERS)
- **Meetings:**
  - Regular Alibaba Cloud Subproject Meeting: [Tuesdays at 12:00 UTC](https://docs.google.com/document/d/1FQx0BPlkkl1Bn0c9ocVBxYIKojpmrS1CFP5h0DI68AE/edit) (monthly 2020 start date: Jan. 7th). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=12%3A00&tz=UTC).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/1x7E2Brzx8rAEI4IIsfOZuZUBIf-J4NTIGuDaKb8z_sM/edit).
    - [Meeting recordings](https://www.youtube.com/playlist?list=PLWpmsLfcyyD7HAhlLTuwmI9KWuoiaN9nO).
### provider-aws
- **Owners:**
  - [kubernetes-sigs/aws-ebs-csi-driver](https://github.com/kubernetes-sigs/aws-ebs-csi-driver/blob/master/OWNERS)
  - [kubernetes-sigs/aws-efs-csi-driver](https://github.com/kubernetes-sigs/aws-efs-csi-driver/blob/master/OWNERS)
  - [kubernetes-sigs/aws-encryption-provider](https://github.com/kubernetes-sigs/aws-encryption-provider/blob/master/OWNERS)
  - [kubernetes-sigs/aws-file-cache-csi-driver](https://github.com/kubernetes-sigs/aws-file-cache-csi-driver/blob/main/OWNERS)
  - [kubernetes-sigs/aws-fsx-csi-driver](https://github.com/kubernetes-sigs/aws-fsx-csi-driver/blob/master/OWNERS)
  - [kubernetes-sigs/aws-fsx-openzfs-csi-driver](https://github.com/kubernetes-sigs/aws-fsx-openzfs-csi-driver/blob/main/OWNERS)
  - [kubernetes-sigs/aws-iam-authenticator](https://github.com/kubernetes-sigs/aws-iam-authenticator/blob/master/OWNERS)
  - [kubernetes-sigs/aws-load-balancer-controller](https://github.com/kubernetes-sigs/aws-load-balancer-controller/blob/main/OWNERS)
  - [kubernetes-sigs/provider-aws-test-infra](https://github.com/kubernetes-sigs/provider-aws-test-infra/blob/master/OWNERS)
  - [kubernetes/cloud-provider-aws](https://github.com/kubernetes/cloud-provider-aws/blob/master/OWNERS)
- **Meetings:**
  - Regular AWS Subproject Meeting: [Fridays at 9:00 PT (Pacific Time)](​​https://zoom.us/j/508079177?pwd=ZmEvMksxdTFTc0N1eXFLRm91QUlyUT09) (biweekly 2019 start date: Jan. 11th). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=9%3A00&tz=PT%20%28Pacific%20Time%29).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/1-i0xQidlXnFEP9fXHWkBxqySkXwJnrGJP9OGyP2_P14/edit).
    - [Meeting recordings](https://www.youtube.com/playlist?list=PL69nYSiGNLP29DzPOBBaJi-SO3AQ_b4HC).
### provider-azure
- **Owners:**
  - [kubernetes-sigs/azuredisk-csi-driver](https://github.com/kubernetes-sigs/azuredisk-csi-driver/blob/master/OWNERS)
  - [kubernetes-sigs/azurefile-csi-driver](https://github.com/kubernetes-sigs/azurefile-csi-driver/blob/master/OWNERS)
  - [kubernetes-sigs/azurelustre-csi-driver](https://github.com/kubernetes-sigs/azurelustre-csi-driver/blob/main/OWNERS)
  - [kubernetes-sigs/blobfuse-csi-driver](https://github.com/kubernetes-sigs/blobfuse-csi-driver/blob/master/OWNERS)
  - [kubernetes-sigs/cloud-provider-azure](https://github.com/kubernetes-sigs/cloud-provider-azure/blob/master/OWNERS)
- **Meetings:**
  - Azure Subproject Meeting: [Tuesdays at 16:00 PT (Pacific Time)](https://zoom.us/j/586836662) (monthly - third Tuesday). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=16%3A00&tz=PT%20%28Pacific%20Time%29).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/1SpxvmOgHDhnA72Z0lbhBffrfe9inQxZkU9xqlafOW9k/edit).
    - [Meeting recordings](https://www.youtube.com/playlist?list=PL69nYSiGNLP2JNdHwB8GxRs2mikK7zyc4).
### provider-equinix-metal
- **Owners:**
  - [kubernetes-sigs/cloud-provider-equinix-metal](https://github.com/kubernetes-sigs/cloud-provider-equinix-metal/blob/main/OWNERS)
### provider-gcp
- **Owners:**
  - [kubernetes-sigs/gcp-compute-persistent-disk-csi-driver](https://github.com/kubernetes-sigs/gcp-compute-persistent-disk-csi-driver/blob/master/OWNERS)
  - [kubernetes-sigs/gcp-filestore-csi-driver](https://github.com/kubernetes-sigs/gcp-filestore-csi-driver/blob/master/OWNERS)
  - [kubernetes/cloud-provider-gcp](https://github.com/kubernetes/cloud-provider-gcp/blob/master/OWNERS)
- **Meetings:**
  - Regular GCP Subproject Meeting: [Thursdays at 16:00 UTC](https://docs.google.com/document/d/1FQx0BPlkkl1Bn0c9ocVBxYIKojpmrS1CFP5h0DI68AE/edit) (biweekly). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=16%3A00&tz=UTC).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/1mtmwZ4oVSSWhbEw8Lfzvc7ig84qxUpdK6uHyJp8rSGU/edit).
### provider-huaweicloud
- **Owners:**
  - [kubernetes-sigs/cloud-provider-huaweicloud](https://github.com/kubernetes-sigs/cloud-provider-huaweicloud/blob/master/OWNERS)
### provider-ibmcloud
- **Owners:**
  - [kubernetes-sigs/cluster-api-provider-ibmcloud](https://github.com/kubernetes-sigs/cluster-api-provider-ibmcloud/blob/main/OWNERS)
  - [kubernetes-sigs/ibm-powervs-block-csi-driver](https://github.com/kubernetes-sigs/ibm-powervs-block-csi-driver/blob/main/OWNERS)
  - [kubernetes-sigs/ibm-vpc-block-csi-driver](https://github.com/kubernetes-sigs/ibm-vpc-block-csi-driver/blob/master/OWNERS)
  - [kubernetes-sigs/provider-ibmcloud-test-infra](https://github.com/kubernetes-sigs/provider-ibmcloud-test-infra/blob/main/OWNERS)
- **Meetings:**
  - Regular IBM Subproject Meeting: [Wednesdays at 14:00 ET (Eastern Time)](https://zoom.us/j/9392903494) (monthly - last Wednesday every month). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=14%3A00&tz=ET%20%28Eastern%20Time%29).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/1qd_LTu5GFaxUhSWTHigowHt3XwjJVf1L57kupj8lnwg/edit).
### provider-oci
- **Owners:**
  - [oracle/cluster-api-provider-oci](https://github.com/oracle/cluster-api-provider-oci/blob/main/OWNERS)
- **Meetings:**
  - Regular Oracle Cloud Subproject Meeting: [Tuesdays at 06:00 PT (Pacific Time)](https://oracle.zoom.us/j/99910180651?pwd=MjhhVC9jZjU3eGIxdjNTYm1UU3V6dz09) (First Tuesday of each month). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=06%3A00&tz=PT%20%28Pacific%20Time%29).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/1mgZxjDbnSv74Vut1aHtWplG6vsR9zu5sqXvQN8SPgCc).
### provider-openstack
- **Owners:**
  - [kubernetes/cloud-provider-openstack](https://github.com/kubernetes/cloud-provider-openstack/blob/master/OWNERS)
- **Meetings:**
  - Regular OpenStack Subproject Meeting: [Wednesdays at 08:00 PT (Pacific Time)](https://docs.google.com/document/d/1bW3j4hFN4D8rv2LFv-DybB3gcE5ISAaOO_OpvDCgrGg/edit) (biweekly starting Wednesday March 20, 2019). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=08%3A00&tz=PT%20%28Pacific%20Time%29).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/15UwgLbEyZyXXxVtsThcSuPiJru4CuqU9p3ttZSfTaY4/edit).
    - [Meeting recordings](https://www.youtube.com/watch?v=iCfUx7ilh0E&list=PL69nYSiGNLP20iTSChQ_i2QQmTBl3M7ax).
### provider-vsphere
- **Owners:**
  - [kubernetes-sigs/vsphere-csi-driver](https://github.com/kubernetes-sigs/vsphere-csi-driver/blob/master/OWNERS)
  - [kubernetes/cloud-provider-vsphere](https://github.com/kubernetes/cloud-provider-vsphere/blob/master/OWNERS)
- **Meetings:**
  - Cloud Provider vSphere monthly syncup: [Wednesdays at 09:00 PT (Pacific Time)](https://zoom.us/j/584244729) (monthly - first Wednesday every month). [Convert to your timezone](http://www.thetimezoneconverter.com/?t=09%3A00&tz=PT%20%28Pacific%20Time%29).
    - [Meeting notes and Agenda](https://docs.google.com/document/d/1B0NmmKVh8Ea5hnNsbUsJC7ZyNCsq_6NXl5hRdcHlJgY/edit?usp=sharing).
    - [Meeting recordings](https://www.youtube.com/playlist?list=PLutJyDdkKQIpOT4bOfuO3MEMHvU1tRqyR).

[subproject-definition]: https://github.com/kubernetes/community/blob/master/governance.md#subprojects
[working-group-definition]: https://github.com/kubernetes/community/blob/master/governance.md#working-groups
<!-- BEGIN CUSTOM CONTENT -->

<!-- END CUSTOM CONTENT -->
