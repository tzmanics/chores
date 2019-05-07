_TABLE tasks // the chores_

| title     | data type   | description                       |
|-----------|-------------|-----------------------------------|
| name      | varchar(80) | what is the task                  |
| location  | varchar(80) | where do you perform the task     |
| duration  | int         | how long does it take to complete |
| frequency | int         | how often must it be done         |
| last_done | date        | when was it last completed        |
| overdue   | bool        | has the due date elapsed          |
| notes     | text        | any details or instructions       |

```
{
('sweep and mop', 'kitchen', 45, 14, '2019-03-01', true, ''),
('sweep and mop', 'downstairs bathroom', 20, 30, '2019-03-01', true, ''),
('sweep and mop', 'dining room', 45, 90, '2019-03-01', true, ''),
('sweep and mop', 'living room', 45, 90, '2019-03-01', true, ''),
('sweep and mop', 'sitting room', 45, 90, '2019-03-01', true, ''),
('sweep and mop', 'nursery/office', 45, 90, '2019-03-01', true, ''),
('sweep and mop', 'upstairs bathroom', 20, 30, '2019-03-01', true, ''),
('sweep and mop', 'bedroom', 45, 90, '2019-03-01', true, ''),
('sweep and mop', 'guest bedroom', 30, 90, '2019-03-01', true, ''),
('water plants', 'upstairs', 20, 7, '2019-03-01', true, ''),
('water plants', 'downstairs', 40, 7, '2019-03-01', true, ''),
('clean fridge', 'kitchen', 60, 120, '2019-03-01', true, ''),
('scrub toilet', 'upstairs bathroom', 15, 14, '2019-03-01', true, ''),
('scrub toilet', 'downstairs bathroom', 15, 14, '2019-03-01', true, ''),
('scrub tub', 'upstairs bathroom', 40, 60, '2019-03-01', true, ''),
('scrub tub', 'downstairs bathroom', 40, 150, '2019-03-01', true, ''),
('clean counter', 'downstairs bathroom', 5, 30, '2019-03-01', true, ''),
('clean counter', 'upstairs bathroom', 5, 7, '2019-03-01', true, ''),
('clean counter', 'kitchen', 30, 60, '2019-03-01', true, 'thorough clean'),
('clean tabletops', 'kitchen', 5, 5, '2019-03-01', true, ''),
('clean tabletops', 'living room', 7, 7, '2019-03-01', true, ''),
('clean tabletops', 'dining room', 5, 7, '2019-03-01', true, ''),
('clean tabletops', 'sitting room', 7, 10, '2019-03-01', true, '')
}
```

_TABLE doers // the people doing the chores_

_TABLE supplies // the things the doers need to do the chores_

