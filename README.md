# How To Help With Climate Mirror
This guide is designed to give you ways to contribute to Climate Mirror, regardless of your skill level. It is a work in progress - 
if you have suggestions or updates, feel free to edit it and submit a pull request (a request to incorporate your changes on GitHub)!

## Mirroring Data
### Hosting or attending a DataRefuge Event
The best way you can help is by attending or hosting a Data Rescue event from our partners at [DataRefuge](http://www.ppehlab.org/datarefuge).
These events gather many volunteers at a space for a day or weekend to collectively copy data. DataRefuge provides a toolkit of information, including the roles each person plays in
archiving data. These events are excellent ways to participate because you get the advice of expert archivists and the quality
of obtained data is high due to the procedures and toolkit they provide. 

 * If you would like to *organize/host* an event, you can [find out more information here](http://www.ppehlab.org/datarescue). 
 You do not need to be a data expert to host an event, but it's a good idea to try partnering with a library. If you're interested
 but have questions, it's worth contacting DataRefuge at the link above.
 * If you are interested in attending an event, you can [see a listing of upcoming events here](http://www.ppehlab.org/datarefuge)
 
### Mirroring Data from Home or Work
If you can't make it to a DataRefuge event or organize an event yourself, you can contribute to ClimateMirror
on your own. To do this, you should:

1. Have some sort of large storage available (ideally publicly accessible)
2. Have a decent working knowledge of using the Internet, including accessing FTP servers.

#### Join us on Slack
Before you mirror data, you should sign up to [join our Slack team](https://climatemirrorslackinvite.herokuapp.com/)
so that you can chat with other members of Climate Mirror about approaches and get help for any issues you're having.

#### Quick start for advanced users

1. Find an issue for [a dataset with "No Mirrors"](https://github.com/climate-mirror/datasets/issues?q=is%3Aissue+is%3Aopen+label%3A%22No+Mirrors%22)
2. Issues with "Size Estimated" labels help you to avoid datasets too large for you to store
3. Check an issue's comments for in progress efforts, move on to another if 2+ people are mirroring already
3. Comment on the issue to let others know you will be mirroring it
4. Start downloading, preserving the structure of the original dataset as much as possible
5. When complete, run `hashdeep -rl $DATASET_DIRECTORY` and save the output along with your mirror
6. Comment again to indicate that you have a mirror and where to access it
7. Repeat for another dataset

#### Getting started in depth

The URLs that need mirroring are listed in our [datasets repository](https://github.com/climate-mirror/datasets/issues).
For those not familiar with using GitHub, each item there is an "issue" - a task that can be tracked. If you click to open each
one, it will have additional details, and a comment thread to help you coordinate with anyone else working to mirror that
dataset. You can filter datasets based on whether they still need mirrors using the labels attached to each issue. [See
here for more information](https://github.com/climate-mirror/datasets/blob/master/labeling_datasets_in_issues.md)
on the labels we use to help you sort datasets.

In some cases, it may be worth checking if the [Internet Archive](http://archive.org) already has a complete mirror of the dataset you are interested in.
Datasets can be added to our issues list by anyone, so a URL's existence there does not indicate that it has been vetted or prioritized, 
or that no other mirrors exist. Once you've identified a dataset you would like to mirror, comment on the issue indicating that you are in the process of
downloading it. When you are done mirroring it (and have checked your mirror to make sure it's complete), comment again
to indicate you have a complete mirror, and if it is available at a publicly accessible URL, please provide the URL as well.

To cross verify each other's mirrors, we compare [hash digests](https://en.wikipedia.org/wiki/Cryptographic_hash_function#Verifying_the_integrity_of_files_or_messages) of the files in the mirrors. A popular tool for calculating hash digests for all files in a mirror is `hashdeep`.

We aim to welcome volunteers and help them to help us. If you have questions, ask them on the Slack channel `#general`.

#### Technology
We currently are not locking anyone to any particular technology. There are many different ways to mirror data, and those
methods depend heavily on what dataset or web site you are trying to copy. In these cases, you will be mostly expected to know
what you are doing to obtain a complete copy. If you feel like you have enough knowledge to start, but have questions, ask us in Slack
or ask for help by commenting on the issue for the dataset.

Soon we plan to post a technology plan for a more long-term set of data mirrors that may include technology proscriptions.
Naturally, these technologies will not be required since you are all volunteers, but we hope you will join us so that we can make
a stronger network of mirrored data.

#### Publicly accessible mirrors
We prioritize mirrors that are made to publicly accessible locations and will not close issues until we have multiple publicly accessible
mirrors available. The reason we prioritize them is because of the large amount of anonymity involved in this volunteer effort,
and because of the complexities of mirroring data. We want them online so we can make sure they exist, and make sure they are complete.

#### Places to store mirrored data
There are many different places that you can store your mirrored data. Some people are building small home servers using Raspberry Pis,
others are storing data in block storage services in the Cloud (such as Amazon's S3). Others are renting servers from places
like Online.net, Scaleway, OVH, and other providers of servers. And still others are storing data in cloud storage services such
as Google Drive and Dropbox (make sure you check your terms of service first). If you want input, chime in on Slack and people can help you
find a good storage option.

## Organizing Data for Other Volunteers
Even if you don't have space for a mirror, you can contribute by helping to organize issues. We call this "issue triage" and it is vitally important:
* making sure all major fields are filled in
* adding labels
* asking people for clarifications and more information (e.g. missing URLs for public mirrors)
* estimating the size of datasets (using tools like `lftp`'s `du` command)
* identifying duplicate issues (multiple issues reference the same dataset, one issue is a subset of another)

## Data Verification

Tools:
Beyond Compare



## Writing Documentation
tools and techniques, how to get people involved, etc.

## Website Improvements



## Seeking out Datasets

Questions and communication: Answering emailed questions

## Organizing Results

## Providing Hosting

## Donating

