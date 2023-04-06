# Advanced Filter and Search Support

Go beyond the use of regular searches, which are limited in scope. Use Gmail Reader to leverage the power of advanced search operators (or special commands and parameters) to dig deeper and narrow your searches when hunting for information.

> Note: You can use words or symbols called search operators to filter your Gmail search results. You can also combine operators to filter your results even more.

## How to use a search operator

1. Login to Gmail Reader
	##### Once installed the app are accessible through the App Launcher 

2. In the search box, type the search operator.
	<img src="../../imgs/query-search_s.jpg" style="max-width:400px" alt="Advanced Filter and Search Support" title="Gmail Reader query search"/>

***
***
***
***
## Operators list.
<table>
	<thead>
		<tr>
			<th style="width:50%">What you can search by	</th>
			<th style="width:50%">Search operator & example</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>
				Specify the sender
			</td>
			<td>
				<p markdown="1">`from:`</p>
				<p markdown="1">Example: `from:amy`</p>
			</td>
		</tr>
		<tr>
			<td>
				Specify a recipient	
			</td>
			<td>
				<p markdown="1">`to:`</p>
				<p markdown="1">Example: `to:david`</p>
			</td>
		</tr>
		<tr>
			<td>
				Specify a recipient who received a copy	
			</td>
			<td>
				<p markdown="1">`cc:`</p>
				<p markdown="1">`bcc:`</p>
				<p markdown="1">Example: `cc:david`</p>
			</td>
		</tr>
		<tr>
			<td>
				Words in the subject line	
			</td>
			<td>
				<p markdown="1">`subject:`</p>
				<p markdown="1">Example: `subject:dinner`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages that match multiple terms	
			</td>
			<td>
				<p markdown="1">`OR` or `{ }`</p>
				<p markdown="1">Example: `from:amy OR from:david`</p>
				<p markdown="1">Example: `{from:amy from:david}`</p>
			</td>
		</tr>
		<tr>
			<td>
				Remove messages from your results		
			</td>
			<td>
				<p markdown="1">`-`</p>
				<p markdown="1">Example: `dinner -movie`</p>
			</td>
		</tr>
		<tr>
			<td>
				Find messages with words near each other. Use the number to say how many words apart the words can be
				Add quotes to find messages in which the word you put first stays first.
			</td>
			<td>
				<p markdown="1">`AROUND`</p>
				<p markdown="1">Example: `holiday AROUND 10 vacation`</p>
				<p markdown="1">Example: `"secret AROUND 25 birthday"`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages that have a certain label	
			</td>
			<td>
				<p markdown="1">`label:`</p>
				<p markdown="1">Example: `label:friends`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages that have an attachment		
			</td>
			<td>
				<p markdown="1">`has:attachment`</p>
				<p markdown="1">Example: `has:attachment`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages that have a Google Drive, Docs, Sheets, or Slides attachment or link		
			</td>
			<td>
				<p markdown="1">`has:drive`</p>
				<p markdown="1">`has:document`</p>
				<p markdown="1">`has:spreadsheet`</p>
				<p markdown="1">`has:presentation`</p>
				<p markdown="1">Example: `has:drive`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages that have a YouTube video		
			</td>
			<td>
				<p markdown="1">`has:youtube`</p>
				<p markdown="1">Example: `has:youtube`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages from a mailing list			
			</td>
			<td>
				<p markdown="1">`list:`</p>
				<p markdown="1">Example: `list:info@example.com`</p>
			</td>
		</tr>
		<tr>
			<td>
				Attachments with a certain name or file type
			</td>
			<td>
				<p markdown="1">`filename:`</p>
				<p markdown="1">Example: `filename:pdf`</p>
				<p markdown="1">Example: `filename:homework.txt`</p>
			</td>
		</tr>
		<tr>
			<td>
				Search for an exact word or phrase
			</td>
			<td>
				<p markdown="1">`" "`</p>
				<p markdown="1">Example: `"dinner and movie tonight"`</p>
			</td>
		</tr>
		<tr>
			<td>
				Group multiple search terms together	
			</td>
			<td>
				<p markdown="1">`( )`</p>
				<p markdown="1">Example: `subject:(dinner movie)`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages in any folder, including Spam and Trash	
			</td>
			<td>
				<p markdown="1">`in:anywhere`</p>
				<p markdown="1">Example: `in:anywhere movie`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages in any folder, including Spam and Trash	
			</td>
			<td>
				<p markdown="1">`is:important`</p>
				<p markdown="1">`label:important`</p>
				<p markdown="1">Example: `is:important`</p>
			</td>
		</tr>
		<tr>
			<td>
				Starred, snoozed, unread, or read messages
			</td>
			<td>
				<p markdown="1">`is:starred`</p>
				<p markdown="1">`is:snoozed`</p>
				<p markdown="1">`is:unread`</p>
				<p markdown="1">`is:read`</p>
				<p markdown="1">Example: `is:read is:starred`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages that include an icon of a certain color
			</td>
			<td>
				<p markdown="1">`has:yellow-star`</p>
				<p markdown="1">`has:blue-info`</p>
				<p markdown="1">Example: `has:purple-star`</p>
			</td>
		</tr>
		<tr>
			<td>
				Recipients in the cc or bcc field
			</td>
			<td>
				<p markdown="1">`cc:`</p>
				<p markdown="1">`bcc:`</p>
				<p markdown="1">Example: `cc:david`</p>
				Note: You can't find messages that you received on bcc.
			</td>
		</tr>
		<tr>
			<td>
				Search for messages sent during a certain time period
			</td>
			<td>
				<p markdown="1">`after:`</p>
				<p markdown="1">`before:`</p>
				<p markdown="1">`older:`</p>
				<p markdown="1">`newer:`</p>
				<p markdown="1">Example: `after:2021/04/16`</p>
				<p markdown="1">Example: `after:04/16/2021`</p>
				<p markdown="1">Example: `before:2021/04/18`</p>
				<p markdown="1">Example: `before:04/18/2021`</p>
			</td>
		</tr>
		<tr>
			<td>
				Search for messages older or newer than a time period using d (day), m (month), and y (year)
			</td>
			<td>
				<p markdown="1">`older_than:`</p>
				<p markdown="1">`newer_than:`</p>
				<p markdown="1">Example: `newer_than:2d`</p>
			</td>
		</tr>
		<tr>
			<td>
				Chat messages	
			</td>
			<td>
				<p markdown="1">`is:chat`</p>
				<p markdown="1">Example: `is:chat movie`</p>
			</td>
		</tr>
		<tr>
			<td>
				Search by email for delivered messages
			</td>
			<td>
				<p markdown="1">`deliveredto:`</p>
				<p markdown="1">Example: `deliveredto:username@gmail.com`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages in a certain category
			</td>
			<td>
				<p markdown="1">`category:primary`</p>
				<p markdown="1">`category:social`</p>
				<p markdown="1">`category:promotions`</p>
				<p markdown="1">`category:updates`</p>
				<p markdown="1">`category:forums`</p>
				<p markdown="1">`category:reservations`</p>
				<p markdown="1">`category:purchases`</p>
				<p markdown="1">Example: `category:updates`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages larger than a certain size in bytes
			</td>
			<td>
				<p markdown="1">`larger:`</p>
				<p markdown="1">`smaller:`</p>
				<p markdown="1">Example: `larger:10M`</p>
			</td>
		</tr>
		<tr>
			<td>
				Results that match a word exactly
			</td>
			<td>
				<p markdown="1">`+`</p>
				<p markdown="1">Example: `+unicorn`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages with a certain message-id header
			</td>
			<td>
				<p markdown="1">`Rfc822msgid:`</p>
				<p markdown="1">Example: `rfc822msgid:200503292@example.com`</p>
			</td>
		</tr>
		<tr>
			<td>
				Messages that have or don't have a label
			</td>
			<td>
				<p markdown="1">`has:userlabels`</p>
				<p markdown="1">`has:nouserlabels`</p>
				<p markdown="1">Example: `has:nouserlabels`</p>
				Note: Labels are only added to a message, and not an entire conversation.
			</td>
		</tr>
	</tbody>
</table>

##### Note: When using numbers as part of your query, a space or a dash (-) will separate a number while a dot (.) will be a decimal. For example, 01.2047-100 is considered 2 numbers: 01.2047 and 100.