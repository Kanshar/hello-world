### Timezones
import pytz
import re
pytz.all_timezones
[tz for tz in pytz.all_timezones if re.match('Australia', tz)]

