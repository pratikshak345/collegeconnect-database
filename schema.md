# CollegeConnect Database Schema

## Users Collection
{
  name: String,
  college: String,
  skills: [String],
  github: String
}

## Forums Collection
{
  title: String,
  description: String,
  createdAt: Date
}

## Events Collection
{
  name: String,
  date: Date,
  location: String
}

## Projects Collection
{
  projectId: String,
  title: String,
  description: String,
  members: [String]
}

## Messages Collection
{
  from: String,
  to: String,
  message: String,
  sentAt: Date
}
